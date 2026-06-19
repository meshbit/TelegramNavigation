# 🧭 Telegram 导航

[🌐 在线访问](https://meshbit.github.io/TelegramNavigation/) · [📦 GitHub 仓库](https://github.com/meshbit/TelegramNavigation)

> 精心整理的 Telegram 群组、频道、机器人合集 — 基于 Hugo + WebStack-Hugo 主题

## 📊 数据统计

- **总收录**：1436 条 · **频道**：1200+ 个 · **群组**：6 个 · **机器人**：200+ 个 · **分类**：15 个

## 🛠️ 技术栈

- [Hugo](https://gohugo.io/) — 静态站点生成器
- [WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo) — 网址导航主题
- 部署于 GitHub Pages

## 🚀 本地开发

```bash
# 安装 Hugo Extended
# Windows: scoop install hugo-extended 或下载二进制

# 克隆并启动
git clone --recurse-submodules https://github.com/meshbit/TelegramNavigation.git
cd TelegramNavigation
hugo server

# 构建
hugo
```

## 📁 项目结构

```
├── config.toml          # 站点配置
├── data/
│   └── webstack.yml     # 导航数据（分类+链接）
├── themes/
│   └── WebStack-Hugo    # 主题（git submodule）
└── public/              # 构建输出（部署到 GitHub Pages）
```

## ⚠️ 声明

数据整理自 [AZeC4/TelegramGroup](https://github.com/AZeC4/TelegramGroup)。内容采集自网络，仅供学习参考。
