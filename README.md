# Next.js App Directory Demo

このリポジトリは Next.js の App Router を用いたのデモプロジェクトです。このプロジェクトは、Next.js と他の一部のライブラリを使用して簡単なメモ帳を作成しています。

## 技術スタック

- Next.js
- React
- TypeScript
- SWR
- Axios
- PostgreSQL
- Prisma

## セットアップ

ローカルでこのプロジェクトを動かすための手順は以下の通りです：

```bash
# リポジトリをクローンします。
git clone https://github.com/s-hiraoku/nextjs-app-directory-demo.git

# プロジェクトのディレクトリに移動します。
cd nextjs-app-directory-demo

# 依存関係をインストールします。
pnpm install

# データベースを初期化します。（PostgreSQLがローカルで動いている必要があります。）
pnpm prisma migrate dev

# デベロップメントサーバーを起動します。
pnpm dev
```

## プロジェクト構成

このプロジェクトは以下のようなディレクトリ構成になっています：

- `/pages`: Next.js のルートとなるページコンポーネントを配置します。
- `/components`: 再利用可能な React コンポーネントを配置します。
- `/contexts`: React の Context を定義します。グローバルなステート管理を行います。
- `/hooks`: カスタムフックを配置します。データの取得や一部のロジックをカプセル化します。
- `/lib`: ヘルパー関数や共通のユーティリティ関数を配置します。
- `/styles`: グローバルスタイルや共通のスタイルコンポーネントを配置します。
- `/types`: TypeScript の型定義を配置します。

## ライセンス

MIT
