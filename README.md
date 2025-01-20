# cloudflare-worker-tailwind

Cloudflare WorkerのStatic Assets上でTailwind CSSを使うサンプルコード

## セットアップ

```bash
pnpm install
```

## ローカル開発

### ビルド

```bash
pnpm run build
```

tailwindcss の watch オプションを有効にしているので、ファイルを更新すると自動でビルドされる。

### ローカル実行

```bash
pnpm run dev
```

### デプロイ

wrangler 未ログインの場合はログインする。

```bash
wrangler login
```

開発環境デプロイ

```bash
pnpm run deploy:dev
```

本番環境デプロイ

```bash
pnpm run deploy:prd
```
