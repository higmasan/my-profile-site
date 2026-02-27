# Astro.jsではじめるモダンWeb開発 第1巻 サンプルコード

[![Built with Astro](https://img.shields.io/badge/Built%20with-Astro-ff5d01?logo=astro&logoColor=white)](https://astro.build)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Node.js](https://img.shields.io/badge/Node.js-18%2B-green)

本リポジトリは、書籍  
『Astro.jsではじめるモダンWeb開発 第1巻 ― はじめてのAstro.js』  
で使用しているサンプルコードです。

本書を読みながら、実際に手を動かして学習できるようになっています。

---

## 📘 このリポジトリで作るもの

個人プロフィールサイト（全5ページ）

- トップページ（自己紹介）
- スキル紹介ページ
- 作品紹介ページ
- お知らせ一覧ページ（Markdown）
- お問い合わせページ

---

## 🧰 動作環境

- Node.js 18以上
- パッケージマネージャー（npm / pnpm / yarn のいずれか）

Node.jsがインストールされているか確認：

```bash
node -v
````

---

## 🚀 セットアップ手順

### 1. リポジトリを取得する

```bash
git remote add origin https://github.com/higmasa/my-profile-site.git
cd my-profile-site
```

または、GitHubの「Code」ボタンからZIPダウンロードも可能です。

---

### 2. パッケージをインストールする

npmの場合：

```bash
npm install
```

pnpmの場合：

```bash
pnpm install
```

---

### 3. 開発サーバーを起動する

```bash
npm run dev
```

または

```bash
pnpm dev
```

ブラウザで表示されるURL（通常は [http://localhost:4321](http://localhost:4321) ）にアクセスしてください。

---

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

---

## 📁 ディレクトリ構成

```
src/
  pages/        ... 各ページ
  layouts/      ... レイアウトコンポーネント
  components/   ... 再利用可能な部品
  styles/       ... グローバルCSS
public/         ... そのまま配信される静的ファイル
```

---

## 📖 書籍との対応


---

## ❓ よくある質問

### Q. エラーが出て起動できません

* Node.jsのバージョンが18以上か確認してください
* `node_modules` を削除して再度 `npm install` を実行してください

### Q. ポート番号が違います

環境によっては `4321` 以外になる場合があります。
ターミナルに表示されたURLをご確認ください。

---

## 📝 ライセンス

MITライセンス

---

## 🌐 書籍について

本書は、HTML/CSSの基礎がある方を対象に、
Astroで静的サイトを作り公開するところまでを丁寧に解説しています。

Astroをこれから始める方は、ぜひ書籍とあわせてご利用ください。

---

Happy Coding 🚀
