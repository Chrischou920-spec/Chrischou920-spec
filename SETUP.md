# 安装与更新 / Setup and updates

## 发布到 GitHub / Publish to GitHub

1. 使用公开同名仓库 `Chrischou920-spec/Chrischou920-spec`，将本包文件放在仓库根目录，默认分支为 `main`。复制时包含隐藏目录 `.github`。
2. 在 Actions 中查看 **Update Contribution Snake**，可手动执行首次更新。工作流每天约上海时间 09:23 运行，GitHub 调度可能延迟；它只提交两张贡献 SVG。
3. 工作流需要 `contents: write`，使用内置 `GITHUB_TOKEN`，无需另建个人令牌。仓库规则需允许机器人向 `main` 推送图片更新。

1. Place the kit at the root of the public profile repository `Chrischou920-spec/Chrischou920-spec`, using `main` as the default branch. Include the hidden `.github` directory.
2. Open **Update Contribution Snake** in Actions and run it manually for an initial refresh. It is scheduled daily at 09:23 in Shanghai, subject to GitHub scheduling delays, and only commits the two contribution SVGs.
3. The workflow needs `contents: write` and uses the built-in `GITHUB_TOKEN`; no personal access token is required. Repository rules must allow the bot to push its image updates to `main`.

## 已包含的内容 / Included content

- Karina 原始 JPEG 与 Hero 中的内嵌图像保持原样。 / The original Karina JPEG and the image embedded in the hero are unchanged.
- 名号为 **AI Product Builder + Crypto**；保留城市、X 和邮箱。 / The identity is **AI Product Builder + Crypto**, with cities, X and email retained.
- 精选项目为原创 Taste Skill、行价比。 / Featured projects are Combinatorial Taste, followed by Xingjiabi.
- 图标为 Python、JavaScript、CSS、MCP、Codex。 / The icon row contains Python, JavaScript, CSS, MCP and Codex.
- 两张蛇动画已使用 Chris 的真实贡献数据生成，可在第一次 Action 运行之前显示；之后每日由同一生成器更新。 / Both snake images were generated from Chris's actual contributions, so they display before the first Action run and are refreshed by the same generator afterward.

## 访问计数 / View counter

使用 [GitHub Profile Views Counter](https://github.com/antonkomarev/github-profile-views-counter)。它累计图片请求产生的页面访问次数，不区分独立访客；GitHub 的图片代理和缓存会影响更新，页面停留期间不会逐秒刷新。该徽章不包含旧主页的历史访问统计。

The [GitHub Profile Views Counter](https://github.com/antonkomarev/github-profile-views-counter) counts page hits through image requests, not unique visitors. GitHub's image proxy and cache affect updates; it does not refresh every second while the page stays open, nor recover historical views from the old profile.

## 动画与素材 / Animation and sources

GitHub README 以 SVG 图片展示动画，不执行页面 JavaScript。Hero 同时提供 `hero-preview.png` 静态版本供减少动态效果的用户使用。素材来源与许可证见 [SOURCES.md](SOURCES.md)。

Animations are SVG images embedded in a GitHub README. The hero also includes `hero-preview.png` for readers who prefer reduced motion. See [SOURCES.md](SOURCES.md) for sources and licenses.
