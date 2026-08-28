# yahoo-framev2

ヤフオク商品画像フレーム編集アプリです。

## 更新方法

`public/index.html` を新しいHTMLに置き換えて、GitHubでコミットします。
Cloudflare Workers Buildsが接続済みなら、自動的に本番へ反映されます。

## Cloudflare設定

- Worker名: `yahoo-framev2`
- Build command: 空欄
- Deploy command: `npx wrangler deploy`
- Root directory: 空欄
- Production branch: `main`
