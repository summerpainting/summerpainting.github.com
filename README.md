# 🎨 牛马手机壳 - 手绘定制手机壳网站

![版本](https://img.shields.io/badge/version-1.0.0-blue.svg)
![状态](https://img.shields.io/badge/status-stable-green.svg)
![维护](https://img.shields.io/badge/maintained-yes-green.svg)

## 🎯 项目简介

牛马手机壳是一个专注于手绘定制手机壳的在线平台，提供个性化定制服务、作品展示和在线订购功能。网站采用现代响应式设计，支持多种设备访问，提供流畅的用户体验。

## ✨ 功能特性

### 🛍️ 核心功能
- **个性化定制**：支持上传图片、选择手机型号、添加个性化文字
- **作品展示**：精美的作品集画廊，分类展示不同类型的手机壳
- **在线订购**：完整的订购流程，支持表单提交和订单跟踪
- **响应式设计**：完美适配桌面、平板、手机等各种设备

### 🎨 设计特色 
- **水印保护**：所有作品图片自动添加水印保护
- **图片预览**：支持图片放大查看，提供高清细节展示
- **主题切换**：支持明暗主题切换

### 🔧 技术亮点
- **纯前端实现**：无需后端服务器，可直接部署到GitHub Pages
- **模块化结构**：清晰的文件组织，便于维护和扩展
- **性能优化**：优化的CSS和JavaScript，确保快速加载
- **SEO友好**：完善的meta标签和语义化HTML结构

## 📁 项目结构

```
summerpainting.github.io/
├── index.html              # 主页
├── html/                   # 内容页面
│   ├── gallery.html         # 作品集
│   ├── products.html        # 产品定制
│   ├── customize.html       # 定制设计
│   ├── about.html          # 关于我们
│   ├── contact.html        # 联系我们
│   ├── order.html          # 在线订购
│   └── ...
├── styles/                 # 样式文件
│   └── style.css          # 主样式文件（包含Fluent Design）
├── images/                 # 图片资源
│   ├── artworks/          # 作品图片
│   ├── icons/             # 图标资源
│   └── hero/              # 首页大图
├── js/                    # JavaScript文件
│   ├── main.js           # 主脚本
│   ├── formspree.js      # 表单处理
│   └── script.js         # 功能脚本
├── components/            # 组件文件
├── data/                 # 数据文件
└── assets/               # 其他资源
```

## 🚀 快速开始

### 本地开发

1. **克隆项目**
   ```bash
   git clone https://github.com/yourusername/summerpainting.github.io.git
   cd summerpainting.github.io
   ```

2. **本地运行**
   ```bash
   # 使用Python启动本地服务器
   python -m http.server 8000
   
   # 或使用Node.js
   npx serve .
   ```

3. **访问网站**
   打开浏览器访问 `http://localhost:8000`

### 部署到GitHub Pages

1. **Fork项目**
   - 在GitHub上Fork此项目

2. **启用GitHub Pages**
   - 进入项目Settings → Pages
   - 选择Source为"Deploy from a branch"
   - 选择main分支和根目录

3. **访问网站**
   - 网站将自动部署到 `https://yourusername.github.io/summerpainting.github.io`

## 🛠️ 技术栈

### 前端技术
- **HTML5**：语义化标记
- **CSS3**：现代样式，Flexbox/Grid布局
- **JavaScript**：ES6+语法，模块化开发

### 设计系统
- **微软Fluent Design**：现代设计语言
- **响应式网格**：Bootstrap风格的栅格系统
- **CSS变量**：主题颜色和样式变量

### 第三方服务
- **Formspree**：表单提交处理
- **Google Fonts**：字体资源
- **Font Awesome**：图标库

## 🎨 定制流程

### 1. 选择产品
- 浏览作品集获取灵感
- 选择手机型号和壳类型

### 2. 上传设计
- 上传个人图片或选择模板
- 添加个性化文字和元素

### 3. 确认订单
- 预览最终效果
- 填写收货信息
- 完成支付

### 4. 制作发货
- 手工绘制制作
- 质量检查
- 快递发货


## 🎯 浏览器兼容性

- ✅ Chrome (90+)
- ✅ Firefox (88+)
- ✅ Safari (14+)
- ✅ Edge (90+)
- ✅ 移动端浏览器

## 🤝 贡献指南

### 如何贡献
1. Fork本项目
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建Pull Request

### 开发规范
- 使用语义化HTML标签
- 遵循BEM命名规范
- 保持代码格式整洁
- 添加必要的注释

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。


<div align="center">
  <p>⭐ 如果这个项目对你有帮助，请给个Star！</p>
  <p>💝 支持我们继续创作更多优质内容</p>

</div>
