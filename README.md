# NuPhy Lab

[English](#english) · [简体中文](#简体中文)

## English

NuPhy Lab is a macOS lighting studio and AI assistant for **AIR65 / AIR75 / AIR100 V3, NODE75 / NODE100 (LP / HP), and Kick75 (ANSI)**. Connect your keyboard by USB and select wired mode. The app detects the model and keeps artwork separate for each keyboard layout.

### Download

[Download NuPhy Lab for Apple Silicon](https://github.com/bohu8264/NuPhyLab-next/releases/latest/download/NuPhyLab-macOS-AppleSilicon.dmg)

Keyboard features require macOS 13.5 or later, and Smart Selection requires macOS 14 or later. The installer is signed with NuPhy's Developer ID and notarized by Apple.

### Install and update

1. Quit NuPhy Lab, open the DMG, and drag **NuPhy Lab** into Applications. Keep the app data folder to retain your artwork, drafts, and settings.
2. Connect your keyboard with a USB data cable and select wired mode. Follow the app's permission and firmware guidance. If the keyboard needs a firmware update, follow the instructions for NuPhyIO.
3. NuPhy Lab checks for app updates automatically. To check manually, choose **Check for Updates** in the application menu or **Settings → About & updates**. If you use 1.0.11 or 1.1.x, install the current app manually once.

### Features

- Paint per-key RGB, create animations, and save your work in the local artwork library.
- Play keyboard games or add key-triggered and audio-reactive effects.
- Use AI Assistant for Codex and Claude Code task status lights and shortcuts.
- Use Smart Selection to translate, summarize, or ask about a selected region with your chosen model service.

### Codex command keys

Enable Codex mode in AI Assistant to use these default commands. AIR65 V3 has no physical function row for automatic F1–F12 takeover.

| Key | Action |
| --- | --- |
| F7 | Standard / Fast |
| F8 | Allow once |
| F9 | Deny |
| F10 | New chat |
| F11 | Hold to dictate and release to finish |
| F12 | Send |

Allow and Deny require a current approval request. Send requires the chat composer to be focused.

### Smart Selection

Add **Smart Selection** in **Feature Center**. Choose a provider and model in **Settings → Models & API**, enter your API key, and grant the permissions shown in the app. Hold the shortcut and drag over a region, then release to translate or summarize. You can also type or dictate a question. The app remembers your choice of 16 translation languages.

Speech is transcribed locally. The app sends selected text and questions to your chosen model service. It includes images when you enable image sending and the model supports it. Your API key is stored in the Mac Keychain.

[English guide](https://github.com/bohu8264/NuPhyLab-next/blob/main/README.en.md) · [Keyboard compatibility](https://github.com/bohu8264/NuPhyLab-next/blob/main/docs/KEYBOARD_COMPATIBILITY.md) · [Release notes](https://github.com/bohu8264/NuPhyLab-next/releases/latest) · [Source code](https://github.com/bohu8264/NuPhyLab-next) · [Report an issue](https://github.com/bohu8264/NuPhyLab-next/issues)

## 简体中文

NuPhy Lab 是面向 **AIR65／AIR75／AIR100 V3、NODE75／NODE100（LP／HP）和 Kick75（ANSI）** 的 macOS 灯效工作室与 AI 助手。用 USB 数据线连接键盘并切到有线模式，软件会自动识别型号，并按键盘布局分别保存作品。

### 下载

[下载 Apple 芯片版 NuPhy Lab](https://github.com/bohu8264/NuPhyLab-next/releases/latest/download/NuPhyLab-macOS-AppleSilicon.dmg)

键盘功能需要 macOS 13.5 或更新版本，智能框选需要 macOS 14 或更新版本。安装包使用 NuPhy 公司 Developer ID 签名，并已通过 Apple 公证。

### 安装与更新

1. 退出 NuPhy Lab，打开 DMG，将 **NuPhy Lab** 拖入「应用程序」。保留本机应用数据，作品、草稿和设置可继续使用。
2. 用 USB 数据线连接键盘并切到有线模式，按软件提示授权及检查固件。如需更新键盘固件，请按指引前往 NuPhyIO。
3. NuPhy Lab 会自动检查更新。也可在应用菜单或 **设置 → 关于与更新** 选择 **检查更新**。使用 1.0.11 或 1.1.x 的用户需先手动安装一次新版。

### 功能

- 逐键绘制 RGB 灯效、制作动画，并将作品保存到本地作品库。
- 玩键盘游戏，或添加按键触发与声音律动效果。
- 在 AI 助手中使用 Codex、Claude Code 的任务状态灯和快捷键。
- 用智能框选调用所选模型服务，翻译、总结选区内容或提问。

### Codex 命令键

在 AI 助手中启用 Codex 模式后可使用以下默认命令键。AIR65 V3 没有实体 F 区，不提供 F1–F12 自动接管。

| 按键 | 操作 |
| --- | --- |
| F7 | 普通／极速 |
| F8 | 批准一次 |
| F9 | 拒绝 |
| F10 | 新聊天 |
| F11 | 按住听写，松开结束 |
| F12 | 发送 |

批准和拒绝需要当前有待处理的审批请求。发送前请聚焦聊天输入框。

### 智能框选

在 **功能中心** 添加 **智能框选**。在 **设置 → 模型与 API** 选择服务和模型，填写自己的 API Key，并按提示授权。按住快捷键拖动框选，松开后即可翻译或总结，也可输入或口述问题。软件支持 16 种翻译目标语言并保存你的选择。

语音在本机转写。选区文字和问题会发送给你所选的模型服务；仅在开启发送图片且模型支持时附带图片。API Key 保存在 Mac 钥匙串中。

[简体中文指南](https://github.com/bohu8264/NuPhyLab-next/blob/main/README.zh-CN.md) · [键盘兼容性](https://github.com/bohu8264/NuPhyLab-next/blob/main/docs/KEYBOARD_COMPATIBILITY.md) · [发行说明](https://github.com/bohu8264/NuPhyLab-next/releases/latest) · [源码](https://github.com/bohu8264/NuPhyLab-next) · [反馈问题](https://github.com/bohu8264/NuPhyLab-next/issues)
