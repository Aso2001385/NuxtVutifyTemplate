# LaravelNuxtTemplate

## このテンプレートリポジトリについて

このテンプレートリポジトリを使うと簡単に Laravel×Nuxt の SPA プロジェクトを作成することができます。
<br>
コミット履歴を残すことなく環境を構築することができ、使いまわすことで環境構築の速度を引き上げることができます。

## 環境構築

### 使用ツール

- [Volta](https://docs.volta.sh/guide/getting-started)を使用して Node.js と yarn をインストールする。

```bash
# インストール
$ curl https://get.volta.sh | bash
# Node.jsインストール
$ volta install node
# yarnインストール
$ volta install yarn
```

### 環境構築リファレンス

- .env.example ファイルの中身をもとに.env ファイルを作成する
- .env ファイルの「YOUR\_~」を自分の好きな名称に書き換える
- 以下を参照して各環境を構築する

* [frontend](./reference/frontend.md)
* [backend](./reference/backend.md)
