# The Reading Room｜私人阅读室

一个无需安装依赖、可直接部署到 GitHub Pages 的个人阅读记录网页。

## 功能

- 添加、编辑和管理计划阅读 / 已读完的书籍
- 上传自定义书籍封面
- 记录总页数、当前阅读页数、每日阅读目标和计划完成日期
- 自动计算阅读进度、剩余页数和截止日期
- 搜索书名或作者，并按阅读状态筛选
- 浏览器本地保存数据

## 本地使用

直接双击 `index.html`，或使用浏览器打开即可。无需安装 Node.js，也无需构建。

## 发布到 GitHub Pages

1. 登录 GitHub，创建一个新仓库（Repository）。
2. 将本项目中的 `index.html`、`README.md` 和 `favicon.ico` 上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/(root)`，点击 **Save**。
6. 等待 GitHub Pages 部署完成，页面会显示可访问的网址。

## 数据与隐私说明

书籍资料和封面保存在当前浏览器的 `localStorage` 中，不会自动上传到 GitHub，也不会自动在不同设备或浏览器之间同步。清除浏览器站点数据可能导致记录丢失，建议定期自行备份。

## 文件结构

```text
reading-room/
├── index.html    # 网页主体，样式和脚本均已内置
├── README.md     # 项目说明与部署教程
└── favicon.ico   # 浏览器标签页图标
```
