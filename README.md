# Astro Starter Kit: Minimal

```sh
npm create astro@latest -- --template minimal
```

> ｧ鯛昨泅 **Seasoned astronaut?** Delete this file. Have fun!

## 噫 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
笏懌楳笏 public/
笏懌楳笏 src/
笏・  笏披楳笏 pages/
笏・      笏披楳笏 index.astro
笏披楳笏 package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## ｧ・Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 操 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## Cloudflare縺ｧ蜈ｬ髢九☆繧句ｴ蜷・
Netlify縺ｮ繧ｯ繝ｬ繧ｸ繝・ヨ雜・℃繧帝∩縺代◆縺・ｴ蜷医・縲，loudflare縺ｫ遘ｻ縺励※蜈ｬ髢九＠縺ｾ縺吶・
Cloudflare縺ｮ險ｭ螳壼､縺ｯ莉･荳九〒縺吶・
- Build command: `npm run build`
- Build output directory: `dist`
- Project name: `aidate-museum`

Cloudflare Workers縺ｧ蜈ｬ髢九☆繧句ｴ蜷医・縲√％縺ｮ繝ｪ繝昴ず繝医Μ縺ｫ縺ゅｋ `wrangler.jsonc` 繧剃ｽｿ縺医∪縺吶・繝ｭ繝ｼ繧ｫ繝ｫ縺九ｉ蜈ｬ髢九☆繧句ｴ蜷医・豬√ｌ縺ｯ莉･荳九〒縺吶・
```powershell
npm.cmd run build
npx.cmd wrangler deploy
```

邂｡逅・判髱｢ `/admin/` 縺ｯ Netlify Identity / Git Gateway 縺ｫ萓晏ｭ倥＠縺ｦ縺・ｋ縺溘ａ縲¨etlify繧貞ｮ悟・縺ｫ繧・ａ繧句ｴ蜷医・縲√せ繝槭・縺九ｉ縺ｮ邂｡逅・婿豕輔ｒ GitHub 縺ｧ縺ｮ邱ｨ髮・√∪縺溘・蛻･CMS縺ｸ蛻・ｊ譖ｿ縺医ｋ蠢・ｦ√′縺ゅｊ縺ｾ縺吶・

## Cloudflare Pages縺ｸ縺ｮ遘ｻ陦梧焔鬆・ｼ亥・蠢・・髄縺托ｼ・
1. 縺ｾ縺壼､画峩繧竪itHub縺ｸ蜿肴丐縺励∪縺吶・
```powershell
git add .
git commit -m "prepare cloudflare deploy"
git push
```

2. Cloudflare縺ｫ繝ｭ繧ｰ繧､繝ｳ縺励∪縺吶・
https://dash.cloudflare.com/

3. 蟾ｦ蛛ｴ繝｡繝九Η繝ｼ縺九ｉ `Workers & Pages` 繧帝幕縺阪∪縺吶・
4. `Create` 縺ｾ縺溘・ `Create application` 繧呈款縺励∪縺吶・
5. `Pages` 繧帝∈縺ｳ縲～Import an existing Git repository` 繧帝∈縺ｳ縺ｾ縺吶・
6. GitHub騾｣謳ｺ繧呈ｱゅａ繧峨ｌ縺溘ｉ險ｱ蜿ｯ縺励∪縺吶ゅΜ繝昴ず繝医Μ縺ｯ `character-site` 繧帝∈縺ｳ縺ｾ縺吶・
7. 險ｭ螳夂判髱｢縺ｧ縺ｯ莉･荳九ｒ蜈･蜉帙＠縺ｾ縺吶・
- Project name: `aidate-museum`
- Production branch: `main`
- Framework preset: `Astro`・医↑縺代ｌ縺ｰ `None` 縺ｧ繧ょ庄・・- Build command: `npm run build`
- Build output directory: `dist`

8. `Save and Deploy` 繧呈款縺励∪縺吶・
9. 繝・・繝ｭ繧､縺悟ｮ御ｺ・☆繧九→縲～https://aidate-museum.uehararyuichiro.workers.dev` 縺ｮ繧医≧縺ｪURL縺瑚｡ｨ遉ｺ縺輔ｌ縺ｾ縺吶・
繧ゅ＠陦ｨ遉ｺ縺輔ｌ縺欟RL縺・`https://aidate-museum.uehararyuichiro.workers.dev` 縺ｧ縺ｯ縺ｪ縺九▲縺溷ｴ蜷医・縲～src/components/BaseLayout.astro` 縺ｮ `siteUrl` 繧貞ｮ滄圀縺ｮCloudflare URL縺ｫ螟画峩縺励※縺上□縺輔＞縲・
10. 谺｡蝗樔ｻ･髯阪・縲∽ｻ翫∪縺ｧ騾壹ｊGit縺ｧ譖ｴ譁ｰ縺ｧ縺阪∪縺吶・
```powershell
git add .
git commit -m "update site"
git push
```

Cloudflare縺隈itHub縺ｸ縺ｮpush繧呈､懃衍縺励※縲∬・蜍輔〒繧ｵ繧､繝医ｒ譖ｴ譁ｰ縺励∪縺吶・


