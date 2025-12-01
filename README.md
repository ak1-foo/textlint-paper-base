# 理系の日本語論文を校正するやつ
句読点や、である調、長すぎる一文を指摘してくれる

詳細は[設定ファイル](.textlintrc.json)を見たら大体わかるかも

## インストール方法
1. 以下のファイルを論文のディレクトリ直下にコピー
    - [.gitignore](.gitignore)
    - [.textlintrc.json](.textlintrc.json)
    - [package.json](package.json)
    - [package-lock.json](package-lock.json)
2. `npm install`
3. (Option) VSCodeの拡張機能で[TextLint](https://marketplace.visualstudio.com/items?itemName=taichi.vscode-textlint)をインストール
