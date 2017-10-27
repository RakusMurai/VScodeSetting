# VScode設定ファイル共有リポジトリ
VScodeの設定ファイルを共有します。  
## 使い方
C:\Users\$(username)\AppData\Roaming\Code\User  
VScodeは上記のファイルに設定ファイルが保存してあります。  
このリポジトリはこのUserファイルを共有してあります。  
適当なフォルダにCloneします。

cd C:\Users\$(username)\AppData\Roaming\Code  
cmd /c mklink USER /D User "C:\$(cloneしたフォルダ)"  
を実行すればこの設定フォルダを適用することができます。

## 導入済み拡張機能一覧
2017.10.28現在
* Beautify
* CodeRunner
* ESLint
* jQuery Code Snippers
* Markdown All in One
* Project Manger