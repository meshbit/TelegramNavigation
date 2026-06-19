<h1 align="center">
  <img src="https://meshbit.github.io/TelegramNavigation/assets/images/logo.svg" height="40" alt="Telegram 导航">
</h1>

<p align="center">
  <strong>精心整理的 Telegram 群组、频道、机器人导航站</strong>
</p>

<p align="center">
  <a href="https://meshbit.github.io/TelegramNavigation/"><img src="https://img.shields.io/badge/🌐_在线访问-meshbit.github.io/TelegramNavigation-2AABEE?style=for-the-badge" alt="在线访问"></a>
  <a href="https://github.com/meshbit/TelegramNavigation"><img src="https://img.shields.io/github/stars/meshbit/TelegramNavigation?style=for-the-badge&color=yellow" alt="GitHub Stars"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/分类-15-2AABEE?style=flat-square" alt="分类">
  <img src="https://img.shields.io/badge/条目-1436+-2AABEE?style=flat-square" alt="条目">
  <img src="https://img.shields.io/badge/Hugo-v0.163.2-ff4088?style=flat-square" alt="Hugo">
  <img src="https://img.shields.io/badge/Theme-WebStack--Hugo-blue?style=flat-square" alt="Theme">
  <img src="https://img.shields.io/badge/Deploy-GitHub%20Pages-brightgreen?style=flat-square" alt="GitHub Pages">
</p>

---

## 📖 简介

本导航站整理了大量优质 Telegram 资源，涵盖群组、频道、机器人三大类型，分 **15 个分类**，共收录 **1,436+ 条目**。

每个条目都包含直达链接和简短描述，支持**暗色模式**、**全文搜索**、**侧边栏快速导航**，帮你轻松找到想要的 Telegram 内容。

> 声明：内容采集自网络公开信息，仅供学习参考。所有频道群组真实性未知，侵权请联系删除。存在广告内容，请自行辨别。

---

## 📊 数据概览

| 分类 | 数量 | 说明 |
|------|:----:|------|
| 📦 资源频道 | **904** | 各类资源分享频道，占比最大的分类 |
| 💬 中文社区 | **112** | 中文讨论群组、兴趣社群 |
| 🤖 趣味工具 | **89** | 实用机器人、自动化工具 |
| 🎮 娱乐休闲 | **66** | 游戏、影视、动漫、娱乐 |
| 🛡️ 群组管理 | **64** | 群管机器人、验证、反垃圾工具 |
| 📰 新闻资讯 | **50** | 新闻频道、时事媒体 |
| 🔍 搜索机器人 | **40** | 各种 Telegram 搜索引擎 bot |
| 💻 技术开发 | **37** | 编程、开源、技术讨论 |
| 🔗 科学上网 | **31** | 网络工具、代理、VPN |
| ₿ 加密货币 | **12** | 区块链、币圈、Web3 |
| 📡 播客与媒体 | **15** | 播客频道、自媒体 |
| 🎁 抽奖机器人 | **8** | Telegram 抽奖活动 bot |
| 🛒 购物优惠 | **5** | 购物信息、优惠分享 |
| 🌍 地区群组 | **2** | 各城市/地区本地群组 |
| 📚 学习教育 | **1** | 学习资源、教育内容 |
| **合计** | **1,436** | |

---

## ✨ 功能特性

- 🔍 **全文搜索** — 支持百度、Google、Bing 等多种搜索引擎，内置站内搜索
- 🌙 **暗色模式** — 一键切换深色主题，夜间浏览更舒适
- 📱 **移动适配** — 响应式设计，手机端体验流畅
- 🏷️ **侧边栏导航** — 按分类快速定位，支持折叠/展开
- 💨 **纯静态** — Hugo 生成，GitHub Pages 托管，加载迅速
- 🎨 **Font Awesome 图标** — 5.15.4 版本，每个分类独立图标

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| [Hugo](https://gohugo.io/) Extended v0.163.2 | 静态站点生成器 |
| [WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo) | 导航站主题 |
| [Font Awesome](https://fontawesome.com/) 5.15.4 | 图标库 |
| [GitHub Pages](https://pages.github.com/) | 免费托管 |
| [GitHub Actions](https://github.com/features/actions) | 可选自动部署 |

---

## 🚀 本地开发

### 环境要求

- [Hugo Extended](https://gohugo.io/installation/) v0.126+

### 快速开始

```bash
# 克隆仓库
git clone https://github.com/meshbit/TelegramNavigation.git
cd TelegramNavigation

# 进入 Hugo 项目目录
cd nav-hugo

# 安装主题子模块
git submodule update --init --recursive

# 启动开发服务器（热重载）
hugo server -D

# 浏览器打开 http://localhost:1313/TelegramNavigation/
```

### 构建部署

```bash
# 构建到 public/ 目录，开启压缩
hugo --gc --minify

# 产物在 public/ 目录，可直接部署到任意静态服务器
```

### 项目结构

```
TelegramNavigation/
├── nav-hugo/                  # Hugo 项目源文件
│   ├── config.toml            # 站点配置
│   ├── data/
│   │   └── webstack.yml       # 📌 核心数据文件（所有条目）
│   ├── layouts/               # 自定义模板（覆盖主题）
│   ├── static/                # 静态资源（logo、图标等）
│   └── themes/
│       └── WebStack-Hugo/     # 主题（Git 子模块）
├── README.md
└── index.html                 # 构建产物
```

---

## 📝 贡献指南

欢迎提交 PR！你可以：

### 添加新条目

编辑 `nav-hugo/data/webstack.yml`，按以下格式添加：

```yaml
- taxonomy: 📦 资源频道          # 分类名（需已存在）
  icon: fas fa-box               # Font Awesome 图标类名
  links:
  - title: 频道名称
    url: https://t.me/username   # Telegram 链接
    description: 简短描述         # 一句话介绍
    logo: https://...            # 图标 URL（可选）
```

### 添加新分类

在 `data/webstack.yml` 中新增一个分类块，然后在 `config.toml` 中配置侧边栏菜单项。

### 改进站点功能

- 修改 `layouts/` 下的模板文件进行定制
- 调整 `config.toml` 中的主题参数
- 优化 `static/` 中的静态资源

---

## 📄 数据来源

数据整理自 [AZeC4/TelegramGroup](https://github.com/AZeC4/TelegramGroup)，感谢原作者对 Telegram 生态的贡献。

---

## ⚠️ 免责声明

- 本导航站内容采集自网络公开信息，仅供学习参考
- 所有频道、群组、机器人的真实性未知，使用前请自行甄别
- 部分内容可能包含广告信息，请用户自行判断，本站不对任何损失负责
- 如涉及侵权内容，请联系删除

---

## 📜 License

MIT © [meshbit](https://github.com/meshbit)
