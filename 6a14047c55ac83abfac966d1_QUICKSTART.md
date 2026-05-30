# 🚀 DeepSeek Token Stats - 快速开始

## 最简单的方式（推荐）

### 方式一：GitHub Actions 自动构建（5分钟搞定）

1. 把这个项目上传到你的 GitHub 仓库
2. 进入 GitHub 仓库的 **Actions** 标签页
3. 等待自动构建完成（约5-10分钟）
4. 下载生成的 APK 文件
5. 安装到手机使用！

### 方式二：本地构建

**前置条件：**
- 安装 Node.js 18+
- 安装 Android Studio

**Windows用户：**
双击运行 `build-apk-simple.bat`

**Mac/Linux用户：**
```bash
bash scripts/build-apk.sh
```

### 方式三：PWA 方式（立即使用）

不想构建APK？没关系！

1. 运行 `pnpm run dev`
2. 用手机浏览器访问显示的地址
3. 点击浏览器菜单 → "添加到主屏幕"
4. 就能像APP一样使用了！

---

## ✨ 功能特性

- 🔐 API密钥安全存储
- 📊 Token余额和使用量显示
- 📈 7天使用趋势图表
- 📱 手机全屏体验
- ⚡ 离线缓存支持

---

## 📱 使用说明

1. 打开APP后进入设置页面
2. 输入你的 DeepSeek API 密钥
3. 点击验证，验证成功后保存
4. 返回仪表盘查看Token使用统计

---

## 💡 提示

- 如果本地构建失败，强烈建议使用 GitHub Actions 方式
- GitHub Actions 是完全免费的
