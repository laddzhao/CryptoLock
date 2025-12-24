# CryptoLock - 本地安全加密工具套件

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/laddzhao/CryptoLock/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/laddzhao/CryptoLock)](https://github.com/laddzhao/CryptoLock)
[![GitHub issues](https://img.shields.io/github/issues/laddzhao/cryptolock)](https://github.com/laddzhao/CryptoLock/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/laddzhao/cryptolock/pulls)

## 🌟 项目简介

CryptoLock 是一个完全在浏览器中运行的本地加密/解密和文件校验工具套件。所有操作都在本地执行，不上传任何数据到服务器，确保您的数据安全。

## ✨ 功能特性

### 🔐 加密工具 (index.html)
- **Argon2id 支持**：优先使用更安全的 Argon2id 算法，自动回退到 PBKDF2
- **AES-GCM 加密**：使用 256 位密钥进行认证加密
- **一次性解密模式**：可选"防君子"模式，同一浏览器只能解密一次
- **密码强度检测**：实时显示密码强度和安全建议
- **多种导出选项**：支持复制密文、下载加密文件

### 📁 文件校验工具 (verify.html)
- **本地 SHA-256 计算**：完全在浏览器中计算文件哈希值
- **双通道验证**：通过不同渠道传输文件和哈希值进行比对
- **文件信息显示**：显示文件名、大小、类型和计算耗时
- **跨平台兼容**：提供 macOS/Linux/Windows 系统的哈希计算命令

## 🚀 快速开始

### 一键下载
您可以直接下载完整的项目压缩包：[Download CryptoLock_Project.zip](https://github.com/laddzhao/CryptoLock/releases/download/v1.0.0/CryptoLock-main.zip)

### 在线使用
也可以直接在线体验：[加密工具](https://laddzhao.github.io/CryptoLock) | [文件校验工具](https://laddzhao.github.io/CryptoLock/verify.html)

### 方法一：直接使用
1. 下载或克隆本项目
2. 在浏览器中打开 `index.html` 或 `verify.html`
3. 无需安装，直接开始使用

### 方法二：从 GitHub 使用
访问项目的 GitHub Pages（如果已配置）或在本地运行：
```bash
git clone https://github.com/laddzhao/CryptoLock.git
cd CryptoLock
# 使用本地服务器运行（推荐）
python -m http.server 8000
# 或直接打开 index.html
```
