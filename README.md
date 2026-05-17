# Allen Sun Personal Homepage

纯静态个人主页。页面可直接打开 `index.html` 预览，也可以通过 GitHub 连接 Netlify 自动发布。

## 文件结构

- `index.html`：完整静态主页
- `assets/`：主页视觉资产
- `netlify.toml`：Netlify 发布配置

## Netlify GitHub 自动部署

在 Netlify 项目中绑定这个 GitHub 仓库：

- Build command：留空
- Publish directory：`.`
- Production branch：`main`

之后每次修改文件并推送到 `main` 分支，Netlify 会自动重新发布。

当前已知 Netlify 项目：

- 控制台：https://app.netlify.com/projects/magnificent-squirrel-3277b9/overview
- 线上地址通常为：https://magnificent-squirrel-3277b9.netlify.app/
