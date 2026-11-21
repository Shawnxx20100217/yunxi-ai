# 更新日志 · Changelog

[首页与下载 · Downloads](README.md)

## 2026-11-21 · macOS [0.4.38](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.38)

启用右上角开关后，即使截图正在上传或 AI 正在生成回复，也可移入右上角隐藏或重新打开聊天窗口。单张和整组截图都会继续上传。

The top-right hot corner now lets you hide or reopen the chat while screenshots upload or the AI writes its reply. Both single captures and batches continue uploading.

## 2026-11-06 · macOS [0.4.37](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.37)

修复 ChatGPT 长对话加载旧消息时误报“对话内容已变化”的问题。页面重新绘制后，应用会核对回复属于本次截图，再显示答案提示。

Fixed a false “conversation changed” warning when ChatGPT loads earlier messages in a long chat. After the page redraws, Parallel Desk matches the reply to the original screenshot before showing the hint.

## 2026-11-04 · macOS [0.4.36](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.36)

新增双侧键模式。用一个键逐张暂存，再用另一个键一次提交，最多 10 张。修复隐藏窗口中多图上传完成后偶尔没有发送，以及 ChatGPT 单字母答案偶尔未显示的问题。

Added a two-button mouse mode. One button collects screenshots and the other submits the group, up to 10 images. Fixed missed sends after batch uploads in a hidden window and missing single-letter hints from ChatGPT.

## 2026-11-03 · macOS [0.4.35](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.35)

可在设置中绑定鼠标侧键。单击截一张全屏图，或按住侧键滚动，在需要保留的位置稍停，松手后整组上传。每组最多 10 张。

You can bind a mouse side button in Settings. Click once for a full-screen capture, or hold the button while scrolling and pause at each section you want to capture. Release to upload the group, up to 10 images.

## 2026-10-27 · macOS [0.4.34](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.34)

新增豆包，支持单张或整组截图上传完成后自动发送、鼠标旁的答案提示和简短答案自动复制。

Added Doubao with automatic sending after single or batch screenshot uploads, answer hints beside the pointer, and automatic copying of short answers.

## 2026-10-26 · macOS [0.4.33](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.33)

修复 ChatGPT 输入框自动换行导致截图上传中断的问题。窗口底部会保留上一次失败的原因，直到开始下一次截图。首次授权检查后，撤销状态在后台刷新。

Fixed interrupted uploads when ChatGPT reformats the text in its input box. The status line keeps the last failure reason until the next capture. License revocation checks refresh in the background after the initial check.

## 2026-10-22 · macOS [0.4.32](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.32)

新增 ChatGPT 简短答案自动复制。开启后，本次截图的回复完成时会复制一次，可直接粘贴。此设置在重启应用后关闭。

Added automatic copying of short answers from ChatGPT. When enabled, the app copies the completed answer to the current screenshot once, ready to paste. The setting resets when the app restarts.

## 2026-10-19 · macOS [0.4.31](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.31)

`Option + P` 切换答案提示，`Option + A` 再显示上一次答案 5 秒，无需重新截图或提问。标签随鼠标移到屏幕边缘时保持原位。

`Option + P` toggles answer hints. `Option + A` recalls the last answer for five seconds without taking a screenshot or asking the AI again. The badge keeps its position relative to the pointer at screen edges.

**2026-10-20 · 安装器修订 / Installer update**  
安装器加入“使用说明”，可在安装前查看快捷键、连截和权限说明。已安装 0.4.31 的用户无需重装。  
The installer gained a usage guide covering shortcuts, batch capture, and permissions. Existing 0.4.31 installations did not need an update.

## 2026-10-17 · macOS & Windows [0.4.30](https://github.com/Shawnxx20100217/yunxi-ai/releases/tag/v0.4.30)

两个平台统一到 0.4.30。Windows 版与 Mac 版均支持设备绑定、离线激活、限时授权和撤销授权。Windows 发布页提供 x64 安装器和 ZIP，以及各自的 SHA-256 校验值。

Both platforms shipped version 0.4.30 with device-bound offline activation, time-limited licenses, and license revocation. The Windows release includes an x64 installer and ZIP with a SHA-256 checksum for each.

## 2026-10-11 · macOS 0.4.24

修复 Retina 屏幕全屏截图的本地存档尺寸。桌面保存完整分辨率的 PNG，上传沿用轻量副本。更新前保存的图片保留原有像素尺寸。

Full-screen captures on Retina displays are saved to the Desktop at full resolution. A smaller copy is used for uploads. Previously saved screenshots keep their original dimensions.
