# Loopit 上线模板动机地图

这是一个无构建步骤、无第三方运行时依赖的静态页面，用于展示 Loopit 上线模板的动机分布与效果判断。

## GitHub Pages

目标公开地址：<https://awoele.github.io/loopit-template-motivation-map/>

仓库默认分支为 `main` 时，`.github/workflows/deploy-pages.yml` 会自动把仓库根目录发布到 GitHub Pages。首次部署前，需要在仓库的 **Settings → Pages → Build and deployment** 中将 Source 设置为 **GitHub Actions**。

## 本地预览

在本目录启动任意静态文件服务器，例如：

```powershell
python -m http.server 4173
```

然后访问 <http://localhost:4173/>。

页面的样式、数据与交互均内嵌在 `index.html` 中；没有外部脚本、字体、图片或接口请求。
