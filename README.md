# 愛館市立郷土資料館サイト

一次創作「愛館市立郷土資料館」のキャラクター、イラスト、小説、博物館館報などをまとめるAstro製の静的サイトです。

## よく使うコマンド

PowerShellでは `npm` ではなく `npm.cmd` を使います。

```powershell
cd C:\Users\USER\Desktop\character-site
npm.cmd run dev
```

一時確認用URL:

```text
http://localhost:4321/
```

本番用にビルドする場合:

```powershell
npm.cmd run build
```

## 公開URL

Cloudflare Workersで公開しています。

```text
https://aidate-museum.uehararyuichiro.workers.dev
```

## Cloudflareへの反映方法

通常はGitHubへpushすると、Cloudflare側で自動的に更新されます。

```powershell
git add .
git commit -m "update site"
git push
```

Cloudflare側の主な設定は以下です。

- Project name: `aidate-museum`
- Build command: `npm run build`
- Build output directory: `dist`
- Production branch: `main`

このリポジトリには `wrangler.jsonc` もあります。ローカルから直接Cloudflareへ反映する場合は、ビルド後に以下を使います。

```powershell
npm.cmd run build
npx.cmd wrangler deploy
```

## 管理画面について

`/admin/` はNetlify Identity / Git Gateway向けのDecap CMS設定です。
現在はGitで編集して公開しているため、普段は使わなくて大丈夫です。

## 画像や本文の追加場所

- 画像: `public/images/uploads/`
- キャラクター: `src/content/characters/`
- イラスト: `src/content/illustrations/`
- 小説: `src/content/novels/`
- 博物館館報: `src/content/columns/`
- お知らせ: `src/content/news/`
- 幻覚広告: `src/content/ads/`