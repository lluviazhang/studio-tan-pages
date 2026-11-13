# Studio Tan · 谭老师钢琴课（GitHub Pages 备用站）

这是 Studio Tan 招生页的独立备用站，发布在 GitHub Pages：

https://lluviazhang.github.io/studio-tan-pages/

## 为什么要单独一个

主站 https://studio-tan.onrender.com 部署在 Render 上，经过 Cloudflare 网络。俄罗斯运营商从 2025 年起会把 Cloudflare 的连接限制在约 16KB，主站在俄罗斯加载不全。GitHub Pages 走 Fastly 网络，不经过 Cloudflare，给俄罗斯的访问者用这个链接。

## 文件

- `index.html`：网页本体，和主站内容相同
- `fonts/`：英文字体 Instrument Serif 和 Inter（SIL OFL 开源授权，授权文本在同一文件夹）
- `favicon.svg`：浏览器标签页小图标
- `.nojekyll`：让 GitHub Pages 原样发布文件

## 更新

主站内容改了以后，把新的 `index.html`（以及改过的字体、图标）复制到这个仓库，推送到 main，一两分钟后自动更新。
