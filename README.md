# 🔭 Watchtower - 个人信息瞭望塔

![iOS](https://img.shields.io/badge/iOS-16.0+-blue.svg)
![Swift](https://img.shields.io/badge/Swift-5.9-orange.svg)
![Python](https://img.shields.io/badge/Python-3.11-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

一个智能的信息监控���用，帮助你追踪关心的人物、公司、股票和网站，每天推送最重要的3条消息。

## ✨ 功能特性

- 📱 **多类型监控**: 支持股票、公司、人物、网址/RSS订阅
- 🎯 **智能筛选**: AI算法每日精选最重要的3条消息
- 🔔 **定时推送**: 自定义推送时间，准时送达重要资讯
- 📊 **历史记录**: 查看过往消息，支持按类型筛选
- 💾 **离线优先**: 本地存储，随时查看历史记录

## 🏗️ 技术栈

### iOS 应用
- SwiftUI + Combine
- Swift 5.9+
- iOS 16.0+
- UserDefaults 本地存储

### 后端服务
- Python FastAPI
- NewsAPI 新闻数据
- Alpha Vantage 股票数据
- RSS Feed 订阅

## 📦 项目结构

```
watchtower/
├── ios/                 # iOS SwiftUI 应用
│   ├── WatchtowerApp/   # 主应用文件
│   ├── Models/          # 数据模型
│   ├── Views/           # UI 视图
│   └── ViewModels/      # 视图模型
├── backend/             # Python FastAPI 后端服务
│   ├── main.py          # 应用入口
│   ├── models/          # 数据模型
│   ├── api/             # API 路由
│   ├── services/        # 业务逻辑
│   └── requirements.txt  # 依赖清单
├── docs/                # 项目文档
└── README.md            # 项目说明
```

## 🚀 快速开始

### iOS 应用

1. 在 Xcode 中创建新的 iOS App 项目
2. 将 `ios/WatchtowerApp/` 下的所有 Swift 文件添加到项目
3. 运行应用 (Cmd+R)

### 后端服务

```bash
cd backend
pip install -r requirements.txt
python main.py
```

## 📱 使用说明

### 添加监控目标
1. 在首页点击 "+"按钮
2. 选择监控类型（股票、公司、人物、网址）
3. 输入相关信息并保存

### 配置推送时间
1. 进入设置界面
2. 选择"推送设置"
3. 设置每日推送时间
4. 保存配置

### 查看历史记录
- 在首页向左滑动即可查看历史消息
- 支持按类型筛选消息

## 🔐 安装 GitHub CLI (macOS)

```bash
# 使用 Homebrew 安装
brew install gh

# 或者从官网下载
# https://cli.github.com/
```

## 🔑 GitHub 认证和推送

```bash
# 登录 GitHub
gh auth login

# 然后推送代码
git push -u origin main
```

## 📄 许可证

本项目采用 MIT 许可证，详见 [LICENSE](LICENSE) 文件

## 👤 作者

- GitHub: [@dingning0506-cyber](https://github.com/dingning0506-cyber)