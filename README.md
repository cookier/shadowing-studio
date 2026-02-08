# Shadowing Studio Pro - PWA Edition

## 🎙️ 语言跟读练习工具

一个渐进式Web应用(PWA)，专为提升口语表达能力而设计。

## ✨ PWA特性

- 📱 移动端优化设计
- 🌐 离线可用
- 🏠 可安装到主屏幕
- 🌙 深色模式支持
- 🎯 专注模式
- ⌨️ 键盘快捷键

## 🚀 本地运行

### 方法1: 使用Python（推荐）
```bash
python -m http.server 8000
```

### 方法2: 使用Node.js
```bash
npx serve .
```

### 方法3: 使用PHP
```bash
php -S localhost:8000
```

### 方法4: 使用Live Server (VSCode)
- 安装Live Server扩展
- 右键点击index.html
- 选择"Open with Live Server"

## 📱 PWA测试

在浏览器中访问 `http://localhost:8000` 并：

1. **测试响应式设计** - 调整窗口大小
2. **测试PWA安装** - Chrome/Edge会显示安装图标
3. **测试离线功能** - 在开发者工具中切换到离线模式
4. **测试移动端** - 使用设备模拟器

## 🎮 使用说明

### 基本操作
- **播放/暂停**: 空格键或START按钮
- **切换句子**: ↑/↓ 方向键
- **单句重复**: R键
- **专注模式**: F键或👁️按钮
- **继续播放**: Enter键
- **停止**: Esc键或■按钮

### 设置选项
- **语音**: 选择不同的语音引擎
- **语速**: 0.5x - 1.5x调节
- **停顿**: 句子间隔时间设置

## 📂 文件结构

```
shadowing-studio/
├── index.html          # 主应用文件
├── manifest.json       # PWA配置
├── sw.js              # Service Worker
├── icon.svg           # 应用图标
└── README.md          # 说明文档
```

## 🌐 部署

### GitHub Pages
1. 推送到GitHub仓库
2. 在Settings > Pages中启用
3. 选择main分支和root目录
4. 访问 `https://用户名.github.io/shadowing-studio/`

### 其他静态托管
该应用可部署到任何静态文件托管服务，如：
- Netlify
- Vercel
- Firebase Hosting
- 等

## 🎯 PWA特性说明

### 移动端优化
- 响应式布局适配各种屏幕
- 触摸交互和反馈
- 虚拟键盘适配
- 安全区域支持（iPhone刘海屏）

### 离线功能
- Service Worker缓存所有资源
- 网络断开仍可正常使用
- 自动更新缓存

### 安装体验
- 浏览器显示安装提示
- 添加到主屏幕
- 全屏独立窗口运行
- 类原生应用体验

## ⌨️ 快捷键

| 快捷键 | 功能 |
|--------|------|
| 空格 | 播放/暂停 |
| ↑/↓ | 上/下句 |
| R | 重复当前句 |
| F | 专注模式 |
| Enter | 继续播放 |
| Esc | 停止播放 |

## 🔧 技术栈

- HTML5 + CSS3 + JavaScript (ES6+)
- Web Speech API
- Service Worker API
- PWA Manifest
- CSS Grid & Flexbox

## 📄 许可证

MIT License