# Parallel Desk · 云隙 AI

macOS 与 Windows 的 AI 悬浮工作区，支持 ChatGPT、Gemini、Grok 和 DeepSeek。

A floating AI workspace for macOS and Windows, with shared product naming, icon naming and offline authorization.

**macOS: 0.4.31（macOS 13+） · Windows: 0.4.30（Windows 10/11 x64）**

## 下载 · Download

按系统选择下载：macOS 本次更新到 [v0.4.31](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.31)，Windows 保持 [v0.4.30](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.30)。

Choose your platform below. This release updates macOS only; Windows remains on v0.4.30.

- [macOS 安装包 · macOS installer](https://github.com/Shawnxx20100217/yunxi-ai/releases/download/v0.4.31/ParallelDesk-0.4.31-installer-macOS.zip)
- [Windows 安装器 · Windows installer](https://github.com/Shawnxx20100217/yunxi-ai/releases/download/v0.4.30/ParallelDesk-Setup-0.4.30-x64.exe)
- [Windows ZIP](https://github.com/Shawnxx20100217/yunxi-ai/releases/download/v0.4.30/ParallelDesk-0.4.30-x64.zip)

## macOS 0.4.31 更新 · What’s new

- **Option + P**：开启／关闭鼠标旁答案提示。Toggle the answer badge.
- **Option + A**：上次答案再显示 5 秒，无需再次截图或调用 AI。Show the last completed answer again for five seconds, without capturing or querying AI again.
- 新截图、取消或关闭提示后清除旧答案。Starting a new capture, cancelling, or turning hints off clears the previous answer.
- 答案标签保持鼠标旁固定位置，允许超出屏幕边缘，不再回弹。The badge follows a fixed offset and can extend past screen edges without snapping inward.

## 功能 · Features

- AI 悬浮窗，可在四个平台之间切换。
- 截图、批量截图、OCR 和网页内文字输入。
- 透明度、置顶、全屏应用上方显示和快捷键。
- macOS 与 Windows 使用同一套 `LC1` 离线授权协议和 `PD1` 设备码体系。
- 限时授权使用本地时钟回拨保护；签名的 `PDR1` 撤销名单可锁定已撤销设备。
- 管理员签发工具保持私有，不随客户包发布；客户包只包含公钥。

## 授权 · Authorization

首次运行时复制设备码，联系管理员签发永久或限时激活码。授权码在本机验证，不发送到服务器。管理员私钥不在本仓库、安装器或客户包中。

On first launch, copy the device code and request a permanent or time-limited activation token from the administrator. Tokens are verified locally and the signing private key is never distributed.

## 联系方式 · Contact

- 微信 / WeChat：**Shawnxx20100217**
- 中国抖音 / Douyin：**Shawnxx20100217**
- 电报 / Telegram：[**@shawnxio**](https://t.me/shawnxio)

本仓库只发布当前客户安装包和说明，不提供源代码、管理员工具或私钥。

This repository publishes the current customer packages and documentation only; source code, administrator tools and private keys are not distributed.
