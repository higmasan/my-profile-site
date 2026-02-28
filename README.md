# Astro.jsではじめるモダンWeb開発 第1巻 サンプルコード

[![Built with Astro](https://img.shields.io/badge/Built%20with-Astro-ff5d01?logo=astro&logoColor=white)](https://astro.build)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Node.js](https://img.shields.io/badge/Node.js-18%2B-green)

本リポジトリは、書籍『Astro.jsではじめるモダンWeb開発 第1巻入門編 はじめてのAstro.js ― 静的サイト制作入門』で使用しているサンプルコードです。

本書を読みながら、実際に手を動かして学習できるようになっています。

## 📘 このリポジトリで作るもの

個人プロフィールサイト（全5ページ）

- トップページ（自己紹介）
- スキル紹介ページ
- 作品紹介ページ
- お知らせ一覧ページ（Markdown）
- お問い合わせページ

## 🧰 動作環境

- Node.js 18以上
- パッケージマネージャー（npm / pnpm / yarn のいずれか）

Node.jsがインストールされているか確認：

```bash
node -v
````

## 🚀 セットアップ手順

### 1. リポジトリを取得する

```bash
git remote add origin https://github.com/higmasan/my-profile-site.git
cd my-profile-site
```

または、GitHubの「Code」ボタンからZIPダウンロードも可能です。

### 2. パッケージをインストールする

npmの場合：

```bash
npm install
```

pnpmの場合：

```bash
pnpm install
```

### 3. 開発サーバーを起動する

```bash
npm run dev
```

または

```bash
pnpm dev
```

ブラウザで表示されるURL（通常は [http://localhost:4321](http://localhost:4321) ）にアクセスしてください。

## 📦 ビルド方法

本番用にビルドする場合：

```bash
npm run build
```

生成されたファイルは `dist/` フォルダに出力されます。

ビルド結果を確認する場合：

```bash
npm run preview
```

## 📁 ディレクトリ構成

```
src/
  pages/        ... 各ページ
  layouts/      ... レイアウトコンポーネント
  components/   ... 再利用可能な部品
  styles/       ... グローバルCSS
public/         ... そのまま配信される静的ファイル
```

## 📌 章ごとの状態に切り替える方法（タグの利用）

本リポジトリでは、各章の完了時点のコードに
`chapter-02` のような **タグ（tag）** を付けています。

本書を読み進める中で、

* 「この章の完成状態を確認したい」
* 「うまく動かないので正解コードを見たい」

という場合は、タグをチェックアウトしてください。

### 🔎 利用可能なタグを確認する

```bash
git tag
```

例：

```
chapter-02
chapter-03
chapter-04
```

### 🔄 特定の章の状態に切り替える

例：第2章の完了状態に切り替える場合

```bash
git checkout chapter-02
```

これで、その章の完成状態のコードになります。

### ⚠ 注意

タグをチェックアウトすると「detached HEAD」状態になります。
そのまま作業を続けたい場合は、新しいブランチを作成してください。

```bash
git checkout -b my-work
```

### 📘 書籍との対応

| 書籍の章    | タグ名        |
| ------- | ---------- |
| 第2章終了時点  | chapter-02 |
| 第3章終了時点  | chapter-03 |
| 第4章終了時点  | chapter-04 |
| 第5章終了時点  | chapter-05 |
| 第6章終了時点  | chapter-06 |
| 第7章終了時点  | chapter-07 |
| 第8章終了時点  | chapter-08 |
| 第9章終了時点  | chapter-09 |
| 第10章終了時点 | chapter-10 |

## ❓ よくある質問

### Q. エラーが出て起動できません

* Node.jsのバージョンが18以上か確認してください
* `node_modules` を削除して再度 `npm install` を実行してください

### Q. ポート番号が違います

環境によっては `4321` 以外になる場合があります。
ターミナルに表示されたURLをご確認ください。

## 📝 ライセンス

MITライセンス

## 🌐 書籍について

本書は、HTML/CSSの基礎がある方を対象に、
Astroで静的サイトを作り公開するところまでを丁寧に解説しています。

Astroをこれから始める方は、ぜひ書籍とあわせてご利用ください。

---

Happy Coding 🚀
