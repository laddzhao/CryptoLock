# 🔐 CryptoLock - 本地安全加密工具

一个完全在浏览器中运行的现代加密工具，使用Argon2id和AES-GCM-256算法，为您的数据加上数字锁。无需安装，无需服务器，一切都在本地安全处理。

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/laddzhao/cryptolock/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/laddzhao/cryptolock)](https://github.com/laddzhao/cryptolock/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/laddzhao/cryptolock)](https://github.com/laddzhao/cryptolock/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/laddzhao/cryptolock/pulls)

## 🎯 核心理念
**"您的数据，您的控制，永不离开您的设备"**

## ✨ 核心特性

### 🔐 军事级加密
- **双重密钥派生**：优先使用 Argon2id（2015年密码哈希竞赛冠军），不支持时自动回退到 PBKDF2
- **AES-GCM-256 加密**：现代认证加密算法，确保数据机密性和完整性
- **零数据泄漏**：所有操作都在浏览器中完成，数据永不离开您的设备

### 🎨 极佳体验
- **响应式设计**：完美适配桌面、平板和手机
- **深色/浅色主题**：自动跟随系统设置
- **实时反馈**：密码强度检查、操作状态提示
- **快捷键支持**：专业级操作效率

### 🔧 强大功能
- **文本加密/解密**：支持任意文本内容
- **文件完整性校验**：SHA-256哈希计算与比对
- **智能预设**：多种安全级别，一键切换
- **完全离线**：下载后无需网络即可使用

## 🚀 快速开始

### 在线体验
访问 [GitHub Pages](https://laddzhao.github.io/CryptoLock/) 直接使用

### 本地部署（推荐）
```bash
# 克隆仓库
git clone https://github.com/laddzhao/cryptolock.git

# 进入目录
cd cryptolock

# 浏览器打开
open index.html  # macOS
start index.html # Windows
xdg-open index.html  # Linux
