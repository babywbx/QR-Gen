# 📱 QR Code Generator

一个简洁美观的在线二维码生成器，支持自定义颜色、大小和实时预览。

🔗 **在线体验：** 部署在 Cloudflare Pages

---

## ✨ 功能特性

- 🎨 **自定义前景色 & 背景色** — 自由搭配颜色组合
- 📐 **可调节尺寸** — 100px ~ 2000px 任意调整
- ⚡ **实时预览** — 输入即生成，所见即所得
- 📋 **一键复制** — 直接复制为图片到剪贴板
- 📥 **快捷下载** — 支持 `⌘S` / `Ctrl+S` 快捷键
- 🌗 **深色模式** — 自动跟随系统，也可手动切换
- 📱 **响应式设计** — 完美适配移动端和桌面端
- 🔒 **纯本地生成** — 无需服务器，数据不上传

## 🛠️ 技术栈

- **HTML / CSS / JavaScript** — 零依赖，单文件应用
- **[qrcode.js](https://github.com/soldair/node-qrcode)** — QR 码生成库（v1.5.1）
- **Cloudflare Pages** — 静态部署，全球 CDN 加速

## 📁 项目结构

```
QR Gen/
├── index.html      # 主应用（HTML + CSS + JS 一体）
├── qrcode.js       # QR 码生成库
├── _headers        # Cloudflare Pages 缓存配置
├── robots.txt      # 搜索引擎爬虫规则
└── README.md
```

## 🚀 部署

本项目为纯静态应用，直接部署到任何静态托管平台即可：

```bash
# Cloudflare Pages — 直接关联 Git 仓库或拖拽上传
# Vercel / Netlify — 同理，零配置部署
```

也可以本地双击 `index.html` 直接打开使用。

## 📜 开源协议

本项目基于 [MIT License](./LICENSE) 开源。

### 第三方依赖

| 库 | 版本 | 协议 | 作者 | 仓库 |
|---|---|---|---|---|
| qrcode | 1.5.1 | MIT | [Ryan Day](https://github.com/soldair) | [soldair/node-qrcode](https://github.com/soldair/node-qrcode) |

---

Made with 💖 by [Babywbx](https://github.com/Babywbx)
