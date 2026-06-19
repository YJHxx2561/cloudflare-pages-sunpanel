# SunPanel 导航页

一个基于 SunPanel 设计的网站导航页，部署在 Cloudflare Pages 上。

## 功能特性

- **随机背景图片** - 每次打开页面自动获取精美的随机壁纸
- **响应式设计** - 支持桌面端和移动端访问
- **多搜索引擎** - 支持 Bing、Google、Baidu 搜索
- **实时时间显示** - 显示当前时间和农历日期
- **玻璃拟态风格** - 现代美观的 UI 设计
- **分类导航** - 常用网站、本地工具、视频资讯等多个分类

## 快速开始

直接在浏览器中打开 `index.html` 即可使用。

## 部署到 Cloudflare Pages

1. 将项目推送到 GitHub 仓库
2. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
3. 进入 Pages 选项卡
4. 创建新项目，选择你的 GitHub 仓库
5. 构建命令留空，输出目录选择 `/`
6. 点击部署

## 项目结构

```
├── index.html          # 主页面
├── 404.html            # 404错误页面
├── SunPanel-Data*.json # 网站数据文件
└── README.md           # 项目说明
```

## 技术栈

- HTML5 + Tailwind CSS 3
- Lucide Icons 图标库
- JavaScript 动态背景加载
- 玻璃拟态设计（Glassmorphism）
