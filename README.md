# MetaMed 中科元医 - 官方网站

> 微瞬间。宏理解。持续精准的力量

## 📋 项目简介

MetaMed 中科元医官方网站，展示 BPER 系统等医疗技术产品的中文版静态网站。

### 🏥 主要产品

- **BPER 系统** - 新一代血压测量设备，实现精确、连续且易于使用的血压监测
- **智能手表** - 全天候健康监测，随时掌握身体状况

### 🌟 技术特点

- **连续测量** - 不间断采集测量数据，全面了解健康状况
- **基于事件的记录** - 对异常或危急健康事件进行专门记录和分析
- **智能数据分析** - 利用人工智能解读数据，提供个性化健康见解

## 🚀 技术栈

- **前端框架**: 静态 HTML/CSS/JavaScript
- **UI 框架**: Webflow 导出的响应式设计
- **样式**: 自定义 CSS + Webflow 组件库
- **脚本**: Vanilla JavaScript + jQuery
- **媒体**: 本地视频和图片资源

## 📁 项目结构

```
├── index.html          # 主页
├── bper.html          # BPER 产品页面
├── forschung.html     # 研究页面
├── uber-uns.html      # 关于我们页面
├── contract.html      # 联系我们页面
├── datenschutz.html   # 隐私政策页面
├── guidelines.html    # 指南页面
├── css/               # 样式文件
│   ├── normalize.css
│   ├── components.css
│   └── micro-giant.css
├── js/                # JavaScript 文件
│   └── micro-giant.js
├── images/            # 图片资源
├── videos/            # 视频资源
└── SECURITY_CHECKLIST.md  # 安全检查报告
```

## 🛡️ 安全特性

本项目已通过全面的安全检查：

- ✅ **Google Safe Browsing 兼容** - 所有外部脚本都来自可信来源
- ✅ **HTTPS 加密** - 所有外部资源使用安全连接
- ✅ **Cookie 同意机制** - 符合 GDPR 要求
- ✅ **隐私政策完整** - 详细的数据处理说明

详细的安全检查报告请查看 [SECURITY_CHECKLIST.md](./SECURITY_CHECKLIST.md)

## 🌐 部署

### 静态部署

项目为纯静态网站，支持部署到任何静态托管服务：

- **Vercel**: 拖拽文件夹即可部署
- **Netlify**: 连接 Git 仓库自动部署
- **GitHub Pages**: 直接从仓库部署
- **AWS S3**: 静态网站托管

### 本地开发

```bash
# 克隆仓库
git clone <your-repo-url>
cd micro-giant.webflow-zh

# 使用本地服务器预览
npx serve .
# 或
python -m http.server 8000
```

## 📱 响应式设计

网站完全响应式，支持：

- 🖥️ 桌面端 (1200px+)
- 💻 笔记本 (768px - 1199px)
- 📱 移动端 (< 768px)

## 🔧 开发工具

- **Webflow** - 视觉设计和原型
- **VS Code** - 代码编辑
- **Git** - 版本控制

## 📊 第三方服务

- **Google Tag Manager** - 网站分析
- **Funnelish** - 转化追踪（已移除）
- **jQuery CDN** - JavaScript 库
- **Finsweet Cookie Consent** - Cookie 管理

## 🚀 性能优化

- ⚡ 压缩的 CSS 和 JavaScript
- 🖼️ 优化的图片和视频
- 📦 CDN 加速的外部资源
- 🔄 异步加载的非关键脚本

## 📞 联系信息

- **邮箱**: info@meta-med.net
- **电话**: 008618824618908
- **网址**: micro-giant.eu

## 📄 许可证

Copyright © 2025 MetaMed 中科元医. All rights reserved.

---

**构建时间**: 2025 年 5 月  
**版本**: 1.0.0
