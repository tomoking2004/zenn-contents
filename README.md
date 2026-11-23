# zenn-contents

Zenn の記事を管理するリポジトリ．記事の作成とプレビューには Zenn CLI を使う．

## 導入

Node.js（22.12 以上）を入れたうえで，このフォルダで次を実行する．

```sh
npm install
```

## 使い方

```sh
npx zenn new:article   # 記事を作る
npx zenn preview       # プレビューを http://localhost:8000 に立てる
```

コマンドの詳細は [Zenn CLIで記事・本を管理する方法](https://zenn.dev/zenn/articles/zenn-cli-guide) を，記事を書くときの決まりは [CLAUDE.md](CLAUDE.md) を参照する．
