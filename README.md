# 松山クリニック

## 開発環境のセットアップ

### 必要な環境

- Node.js

## インストール手順

1. テーマディレクトリへ移動

```bash
cd wp-content/themes/matsuyama-clinic
```

2. 依存関係をインストール

```bash
npm install
```

## 開発の開始

### ライブリロード（Vite）

ファイルを編集すると、自動でブラウザがリロードされます。

```bash
npm run dev
```

実行後、ターミナルに表示される URL（通常は以下）にアクセスしてください。

```
http://localhost:5173/
```

### Sass（SCSS）のコンパイル

SCSS を監視し、CSS を自動生成します。

```bash
npm run sass
```

#### ディレクトリ構成

```
assets/
├─ scss/   → 編集用 SCSS
└─ css/    → 自動生成される CSS（編集しない）
```
