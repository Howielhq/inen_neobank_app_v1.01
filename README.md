# INEN 盈安 · App 原型

纯静态单页原型（HTML + CSS + JS，无构建步骤）。

## 部署到 Vercel

方式一：网页拖拽
1. 打开 https://vercel.com/new
2. 选择 “Deploy” 下的上传 / 拖拽，把整个文件夹拖进去
3. Framework Preset 选 “Other”，Build Command 和 Output Directory 留空
4. 点击 Deploy

方式二：命令行
```bash
npm i -g vercel
cd inen-app
vercel          # 预览环境
vercel --prod   # 正式环境
```

方式三：GitHub
把文件夹推到一个 GitHub 仓库，在 Vercel 导入该仓库即可，之后每次 push 自动部署。

## 说明
- 页面数据均为演示数据，刷新即重置。
- 字体来自 Google Fonts，无法访问时会自动回退到系统字体。
- 手机打开后可“添加到主屏幕”，以全屏方式使用。
