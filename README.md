# 🎽 叽大人的衣帽间 PWA版本

## 📱 安装方法

### 方法一：直接安装（推荐）
1. 将整个 `pwa_衣帽间` 文件夹上传到支持HTTPS的服务器
2. 用手机Chrome浏览器访问 index.html
3. 点击浏览器菜单 → "添加到主屏幕"

### 方法二：打包成APK
详见《PWA打包APK教程.md》

## 📂 文件说明
- `index.html` - 主应用文件（包含所有CSS、JS、图片）
- `manifest.json` - PWA配置文件
- `sw.js` - Service Worker（支持离线访问）

## ✨ 功能特性
- ✅ 离线可用
- ✅ 添加到主屏幕
- ✅ 全屏运行
- ✅ 数据本地存储

## 🔧 本地测试
需要通过本地服务器运行，不能直接双击打开：
- Windows: 双击 `启动本地服务器.bat`
- Mac/Linux: 在pwa_衣帽间目录下运行 `python3 -m http.server 8080`
