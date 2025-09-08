# Crypto Data Hub - GitHub Pages Website

🚀 **Live Website:** [https://brewnut.github.io/wasabi/](https://brewnut.github.io/wasabi/)

## 📁 文件夹说明

这个`github-pages`文件夹包含了完整的GitHub Pages网站配置：

```
github-pages/
├── _config.yml          # Jekyll配置文件
├── index.html           # 英文主页
├── chinese.html         # 中文页面
└── README.md           # 本说明文件
```

## 🌐 双语网站

- **🇺🇸 English**: [Main Page](https://brewnut.github.io/wasabi/)
- **🇨🇳 中文**: [Chinese Page](https://brewnut.github.io/wasabi/chinese.html)

## 🚀 部署到GitHub Pages

### 方法1: 使用docs文件夹部署

1. **重命名文件夹**（推荐）：
   ```bash
   mv github-pages docs
   ```

2. **提交更改**：
   ```bash
   git add docs/
   git commit -m "Add GitHub Pages website in docs folder"
   git push origin main
   ```

3. **在GitHub仓库设置中**：
   - 进入 Settings > Pages
   - Source 选择 "Deploy from a branch"
   - Branch 选择 "main"
   - Folder 选择 "/docs"
   - 点击 Save

### 方法2: 使用子目录部署

1. **保持当前文件夹名**：
   ```bash
   git add github-pages/
   git commit -m "Add GitHub Pages website in github-pages folder"
   git push origin main
   ```

2. **在GitHub仓库设置中**：
   - 进入 Settings > Pages
   - Source 选择 "Deploy from a branch"
   - Branch 选择 "main"
   - Folder 选择 "/github-pages"
   - 点击 Save

## 📊 网站内容

### 产品展示
- **历史数据档案**: $150 (原价$300) - ETH + BTC完整历史数据
- **月度订阅**: $20 (原价$50) - 最新月份数据
- **单个币种**: $20 (原价$50) - 单个加密货币数据

### 数据特性
- **8个时间框架**: 1秒到日线数据
- **专业品质**: 清洁的CSV格式，包含OHLCV数据
- **历史深度**: 2022年到2025年8月完整数据
- **易于访问**: 有序的文件夹结构

## 🛠️ 自定义修改

- **修改英文内容**: 编辑 `index.html`
- **修改中文内容**: 编辑 `chinese.html`
- **修改网站配置**: 编辑 `_config.yml`

修改后推送到GitHub，网站会自动更新。

## 📞 联系方式

📧 **Email**: contact@cryptodatahub.com

---

**为全球交易者和研究人员提供专业区块链数据** 📈
