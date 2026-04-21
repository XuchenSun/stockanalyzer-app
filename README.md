# 股智 StockPulse AI - 官方网站

AI驱动的iOS股票分析应用官方网站，托管于 GitHub Pages。

## 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 应用首页/落地页 |
| `privacy.html` | 隐私政策（中英双语，带语言切换） |
| `support.html` | 帮助支持页面（FAQ + Bug报告模板） |
| `deploy.sh` | 一键部署脚本 |

## 快速部署

### 前提条件
- macOS 系统
- 已安装 [Homebrew](https://brew.sh)（脚本会自动安装 `gh` CLI）
- GitHub 账号

### 部署步骤

1. 打开终端（Terminal）
2. 进入本目录：
   ```bash
   cd ~/Desktop/stockanalyzer-site
   ```
3. 运行部署脚本：
   ```bash
   chmod +x deploy.sh
   bash deploy.sh
   ```
4. 首次运行会打开浏览器进行 GitHub 授权登录
5. 脚本会自动创建仓库、推送代码、启用 GitHub Pages

### 部署完成后

网站将在以下地址可用：
- 首页: `https://<你的用户名>.github.io/stockanalyzer-app/`
- 隐私政策: `https://<你的用户名>.github.io/stockanalyzer-app/privacy.html`
- 支持页面: `https://<你的用户名>.github.io/stockanalyzer-app/support.html`

## 联系方式

📧 sunxuchen1991@gmail.com
