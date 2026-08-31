# Qingtan Labs 项目展示

<p align="center">
  <a href="README.md">English</a> · <strong>简体中文</strong>
</p>

这里集中展示 [Qingtan Labs](https://github.com/qingtan-labs) 维护的公开应用和浏览器扩展。

## macOS 应用

### [DeepSeek Harness for macOS](https://github.com/qingtan-labs/deepseek-harness-macos)

一款面向 DeepSeek Harness（DSH）的原生 macOS Dock 与菜单栏控制器。它可以管理本地 DSH 服务，优先复用已有的 Harness 浏览器标签页，并支持可选的应用内窗口。配置时会先保留并复用用户已经安装的兼容 DSH/Node 环境，确有缺失时才补装隔离组件。

- **主要功能：** 单文件 DMG、现有环境优先、Dock 与菜单栏入口、浏览器标签页复用、服务健康与用户确认更新控制、登录时启动、英文与简体中文界面，以及同时支持 Apple 芯片和 Intel Mac 的通用版本
- **系统要求：** macOS 13 Ventura 或更高版本
- **开源许可：** MIT
- **项目性质：** 独立社区项目，与 DeepSeek 不存在隶属、认可或官方支持关系
- **发行安全：** 当前版本采用临时签名且未经过 Apple 公证；首次运行请按住 Control 点击并选择“打开”，不要关闭 Gatekeeper
- **相关链接：** [最新版与下载](https://github.com/qingtan-labs/deepseek-harness-macos/releases/latest) · [源代码](https://github.com/qingtan-labs/deepseek-harness-macos) · [安装说明](https://github.com/qingtan-labs/deepseek-harness-macos/blob/main/docs/installation.md) · [English](https://github.com/qingtan-labs/deepseek-harness-macos/blob/main/README.md)

### [StatusPerch](https://github.com/qingtan-labs/StatusPerch)

一款轻量、原生的 macOS 菜单栏收纳工具。将低频状态图标放到可移动边界的左侧，即可通过箭头一键收起或展开。

- **主要功能：** 一键收起与展开、按住 Command 拖动调整位置、定时自动收起、登录时启动、英文与简体中文、完全本地运行，无需账户、分析统计、屏幕录制或辅助功能权限，以及同时支持 Apple 芯片和 Intel Mac 的通用版本
- **系统要求：** macOS 13 Ventura 或更高版本
- **授权方式：** 专有免费软件
- **发行安全：** 当前版本采用临时签名且未经过 Apple 公证；请遵循安全安装说明，不要关闭 Gatekeeper
- **官方链接：** [产品官网](https://qingtan-labs.github.io/StatusPerch/) · [官方下载](https://github.com/qingtan-labs/StatusPerch/releases/latest) · [安全安装](https://github.com/qingtan-labs/StatusPerch/blob/main/docs/user-manual/zh-Hans/1-installation.md) · [项目仓库](https://github.com/qingtan-labs/StatusPerch) · [English manual](https://github.com/qingtan-labs/StatusPerch/blob/main/docs/user-manual/en/README.md) · [简体中文手册](https://github.com/qingtan-labs/StatusPerch/blob/main/docs/user-manual/zh-Hans/README.md) · [隐私说明](https://github.com/qingtan-labs/StatusPerch/blob/main/PRIVACY.md) · [支持](https://github.com/qingtan-labs/StatusPerch/blob/main/SUPPORT.md)

## Windows 应用

### [DeepSeek Harness for Windows](https://github.com/qingtan-labs/deepseek-harness-windows)

一款面向 DeepSeek Harness 的原生 Windows 一键控制器。它使用隔离且经过验证的私有运行环境，默认复用已有浏览器标签页，支持可选的 WebView2 应用内窗口，并通过系统托盘管理服务、更新和登录启动。

- **主要功能：** 一键安装、浏览器标签页复用、可选应用内窗口、系统托盘控制、手动更新检查、登录时启动、英文与简体中文，以及 x64/ARM64 支持
- **系统要求：** Windows 10 22H2 或 Windows 11、x64 或 ARM64，以及 .NET Framework 4.8
- **开源许可：** MIT
- **项目性质：** 独立社区项目，与 DeepSeek 不存在隶属、认可或官方支持关系
- **安装方式：** 默认按用户安装，不需要管理员权限；发行文件同时提供 SHA-256 校验值
- **发行安全：** 当前版本尚未进行 Authenticode 签名，Windows SmartScreen 可能显示未知发布者警告
- **相关链接：** [最新版与下载](https://github.com/qingtan-labs/deepseek-harness-windows/releases/latest) · [源代码](https://github.com/qingtan-labs/deepseek-harness-windows) · [安装说明](https://github.com/qingtan-labs/deepseek-harness-windows/blob/main/docs/installation.md) · [安全说明](https://github.com/qingtan-labs/deepseek-harness-windows/blob/main/SECURITY.md) · [English](https://github.com/qingtan-labs/deepseek-harness-windows/blob/main/README.md)

## Chrome 浏览器扩展

相关项目将在发布后添加到这里。
