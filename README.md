# 世界级个人介绍网站

一个现代化、响应式的个人介绍网站，具有炫酷的动画效果和交互体验。

## 特色功能

- 🎨 **现代化设计** - 采用最新的设计趋势，暗色主题配色
- ✨ **炫酷动画** - 3D粒子背景、打字机效果、悬浮动画
- 📱 **完全响应式** - 适配所有设备尺寸
- 🚀 **高性能** - 优化的代码和资源加载
- 🎯 **交互体验** - 平滑滚动、3D卡片效果、视差动画
- 💎 **现代技术** - HTML5、CSS3、ES6 JavaScript

## 文件结构

```
my_introduce/
├── index.html      # 主页面文件
├── style.css       # 样式文件
├── script.js       # JavaScript 交互文件
└── README.md       # 说明文档
```

## 快速开始

1. 下载所有文件到本地目录
2. 用浏览器打开 `index.html` 文件
3. 享受你的个人网站！

## 个人信息修改指南

### 基本信息修改

在 `index.html` 文件中修改以下内容：

**个人姓名和职位** (第43-50行)：
```html
<span class="name">你的姓名</span>
<span id="typewriter"></span> <!-- 打字机效果的职位会在JS中设置 -->
```

**个人描述** (第53-56行)：
```html
<p class="hero-description">
    在这里写你的个人简介和专业特长
</p>
```

**头像图片** (第77-80行)：
```html
<img src="你的头像链接" alt="你的姓名">
```

**联系信息** (第264-289行)：
```html
<!-- 修改地址、邮箱、电话等信息 -->
```

### 技能和项目修改

**技能列表** (第147-243行)：
- 修改技能名称
- 调整技能熟练度 (`data-skill` 属性)
- 添加新的技能分类

**项目展示** (第245-337行)：
- 更换项目图片链接
- 修改项目标题和描述
- 更新技术标签

### 打字机效果修改

在 `script.js` 文件的第35-42行修改职位列表：

```javascript
const texts = [
    '你的职位1',
    '你的职位2',
    '你的职位3',
    '你的职位4'
];
```

### 统计数字修改

在 `index.html` 文件第121-135行修改统计信息：

```html
<div class="stat-number" data-target="你的项目数量">0</div>
<div class="stat-number" data-target="你的获奖数量">0</div>
<div class="stat-number" data-target="你的客户数量">0</div>
```

### 社交媒体链接

在第68-80行和第344-358行修改社交媒体链接：

```html
<a href="你的GitHub链接" class="social-link">
<a href="你的LinkedIn链接" class="social-link">
<a href="你的Twitter链接" class="social-link">
```

## 自定义样式

### 颜色主题修改

在 `style.css` 文件的第8-23行修改颜色变量：

```css
:root {
    --primary-color: #你的主色调;
    --secondary-color: #你的次要色调;
    --accent-color: #你的强调色;
    /* 其他颜色变量... */
}
```

### 添加新的动画效果

参考现有的 CSS 动画，在文件底部添加新的 `@keyframes` 规则。

## 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 现代样式和动画
- **JavaScript ES6** - 交互功能
- **Particles.js** - 粒子背景效果
- **Font Awesome** - 图标库
- **Google Fonts** - 字体

## 性能优化

- 图片懒加载
- 滚动事件防抖
- CSS 动画硬件加速
- 代码分块加载

## 部署建议

### GitHub Pages
1. 创建 GitHub 仓库
2. 上传所有文件
3. 在设置中启用 Pages

### Netlify
1. 将文件拖拽到 Netlify
2. 自动部署完成

### Vercel
1. 连接 GitHub 仓库
2. 一键部署

## 注意事项

1. 确保所有图片链接有效
2. 测试所有设备上的响应式效果
3. 检查社交媒体链接
4. 定期更新项目展示

## 支持

如果你在使用过程中遇到问题，可以：
1. 检查浏览器开发者工具的控制台
2. 确保所有文件在同一目录下
3. 验证外部资源链接是否有效

---

**享受你的新网站！** 🚀