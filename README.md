# 通販サイトプロジェクト

このプロジェクトは、モバイルファーストで設計されたシンプルかつ機能的な通販サイトを構築することを目的としています。Laravelをバックエンドに、Reactをフロントエンドに使用して開発されています。

## プロジェクト概要

- **目的**: 幅広い年齢層のユーザーに使いやすいオンラインショッピングプラットフォームを提供する。
- **特徴**:
  - レスポンシブ対応
  - カート機能、購入履歴機能
  - 管理者用ダッシュボード
  - 商品検索とフィルタリング機能

## 技術スタック

### バックエンド
- Laravel (PHP)
- MySQL
- Laravel Sail (Docker)

### フロントエンド
- React
- TypeScript
- Tailwind CSS
- Material UI

### その他
- Docker
- Git & GitHub

## 主な機能

### ユーザー機能
- ユーザー登録とログイン
- 商品検索・フィルタリング
- カートに商品を追加・編集・削除
- 購入履歴の閲覧

### 管理者機能
- 商品の登録、編集、削除
- カテゴリの管理
- 注文の管理
- 通知の作成と送信

## ディレクトリ構成

```
EcommerceProject/
├── backend/                # Laravel関連ファイル
├── frontend/               # React関連ファイル
├── database/               # マイグレーションファイル
├── docker-compose.yml      # Docker設定
└── README.md               # このファイル
```

## 開発環境のセットアップ

### 必要なソフトウェア
- Docker
- Node.js
- Composer

### 手順
1. リポジトリをクローン:
   ```bash
   git clone https://github.com/AllmayJapan/EcommerceProject.git
   cd EcommerceProject
   ```

2. Dockerコンテナを起動:
   ```bash
   docker-compose up -d
   ```

3. フロントエンドのセットアップ:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

4. バックエンドのセットアップ:
   ```bash
   cd backend
   composer install
   php artisan migrate
   ```

5. ブラウザでアクセス:
   - フロントエンド: `http://localhost:3000`
   - バックエンド: `http://localhost:8000`

## 使用方法

### 商品の購入
1. 商品をカートに追加
2. カートページで商品内容を確認
3. 購入手続きを進める

### 管理者向け
1. 管理者ページにログイン
2. 商品管理セクションで商品の登録・編集・削除を実施

## 今後の改善予定
- おすすめ商品のレコメンド機能
- ユーザーのレビュー・評価機能
- SNS連携ログイン

## 貢献

プロジェクトへの貢献を歓迎します。以下の手順でPull Requestを送ってください。

1. リポジトリをフォーク
2. `feature/<機能名>` ブランチを作成
3. コードを変更し、コミット
4. プルリクエストを作成

## ライセンス

このプロジェクトはMITライセンスの下で提供されています。

