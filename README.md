# Qingtan Labs Project Showcase

<p align="center">
  <strong>English</strong> · <a href="README.zh-Hans.md">简体中文</a>
</p>

A curated catalog of public applications and browser extensions maintained by [Qingtan Labs](https://github.com/qingtan-labs).

## Cross-Platform Product Families

### [DeepSeek Harness Desktop](https://github.com/qingtan-labs/deepseek-harness-desktop)

The unified home for Qingtan Labs' native DeepSeek Harness controllers on macOS and Windows. It gives users one stable product entry point while each platform keeps its own native source, CI, issue tracker, release history, and version cadence.

- **Platforms:** macOS 13+ on Apple silicon/Intel, and Windows 10 22H2 or Windows 11 on x64/ARM64
- **Downloads:** Latest platform releases and SHA-256 verification files remain in the authoritative macOS and Windows repositories
- **License:** MIT
- **Project status:** Independent community projects; not affiliated with or endorsed by DeepSeek
- **Official links:** [Unified project home](https://github.com/qingtan-labs/deepseek-harness-desktop) · [Latest macOS release](https://github.com/qingtan-labs/deepseek-harness-macos/releases/latest) · [Latest Windows release](https://github.com/qingtan-labs/deepseek-harness-windows/releases/latest) · [简体中文](https://github.com/qingtan-labs/deepseek-harness-desktop/blob/main/README.zh-Hans.md)

## macOS Applications

### [Gauge for Codex](https://gauge-for-codex.r9rgtcrw5g.chatgpt.site)

A focused native macOS menu bar utility for seeing Codex remaining quota, every available usage window, and the exact local reset time without leaving the current workspace.

- **Highlights:** Always-visible percentage and progress indicator, every available usage window, localized reset countdown and exact time, 60-second automatic refresh, last-known-good fallback, manual entry fallback, English/Simplified Chinese/Japanese/Spanish, and a universal Apple silicon/Intel build
- **Privacy:** Local-first operation with no analytics, advertising, telemetry, developer account system, or developer-operated backend; it does not read prompts or conversation content
- **Requirements:** macOS 12 Monterey or later and a signed-in Codex installation
- **License:** MIT
- **Project status:** Unofficial third-party utility; not affiliated with or endorsed by OpenAI
- **Release trust:** The current release is ad-hoc signed and not Apple-notarized; use Control-click **Open** and never disable Gatekeeper
- **Official links:** [Product website](https://gauge-for-codex.r9rgtcrw5g.chatgpt.site) · [Latest DMG, ZIP, and checksums](https://github.com/qingtan-labs/GaugeForCodex/releases/latest) · [Source code](https://github.com/qingtan-labs/GaugeForCodex) · [Privacy](https://github.com/qingtan-labs/GaugeForCodex/blob/main/PRIVACY.md) · [简体中文](https://github.com/qingtan-labs/GaugeForCodex/blob/main/README.zh-Hans.md)

### [DeepSeek Harness for macOS](https://github.com/qingtan-labs/deepseek-harness-macos)

A native Dock and menu bar controller for DeepSeek Harness (DSH). It manages the local service, reuses an existing Harness browser tab whenever possible, and provides an optional in-app window. Setup preserves and reuses a compatible user-installed DSH/Node environment before adding any isolated fallback components.

- **Highlights:** Single-file DMG, existing-environment-first setup, Dock and menu bar access, browser-tab reuse, service health controls, staged DSH update validation before activation, login startup, English and Simplified Chinese, and a universal Apple silicon/Intel build
- **Requirements:** macOS 13 Ventura or later
- **License:** MIT
- **Project status:** Independent community project; not affiliated with or endorsed by DeepSeek
- **Release trust:** The current release is ad-hoc signed and not Apple-notarized; use Control-click **Open** and never disable Gatekeeper
- **Links:** [Latest release and download](https://github.com/qingtan-labs/deepseek-harness-macos/releases/latest) · [Source code](https://github.com/qingtan-labs/deepseek-harness-macos) · [Installation guide](https://github.com/qingtan-labs/deepseek-harness-macos/blob/main/docs/installation.md) · [简体中文](https://github.com/qingtan-labs/deepseek-harness-macos/blob/main/README.zh-Hans.md)

### [StatusPerch](https://github.com/qingtan-labs/StatusPerch)

A lightweight native macOS menu bar organizer. Place low-frequency status items to the left of a movable boundary, then hide or reveal them with one click.

- **Highlights:** One-click hide and reveal, Command-drag positioning, timed auto-hide, login startup, English and Simplified Chinese, fully offline operation without accounts, analytics, Screen Recording, or Accessibility permissions, and a universal Apple silicon/Intel build
- **Requirements:** macOS 13 Ventura or later
- **License:** Proprietary freeware
- **Release trust:** The current release is ad-hoc signed and not Apple-notarized; follow the safe installation guide and never disable Gatekeeper
- **Official links:** [Product website](https://qingtan-labs.github.io/StatusPerch/) · [Official downloads](https://github.com/qingtan-labs/StatusPerch/releases/latest) · [Safe installation](https://github.com/qingtan-labs/StatusPerch/blob/main/docs/user-manual/en/1-installation.md) · [Project repository](https://github.com/qingtan-labs/StatusPerch) · [English manual](https://github.com/qingtan-labs/StatusPerch/blob/main/docs/user-manual/en/README.md) · [简体中文手册](https://github.com/qingtan-labs/StatusPerch/blob/main/docs/user-manual/zh-Hans/README.md) · [Privacy](https://github.com/qingtan-labs/StatusPerch/blob/main/PRIVACY.md) · [Support](https://github.com/qingtan-labs/StatusPerch/blob/main/SUPPORT.md)

## Windows Applications

### [DeepSeek Harness for Windows](https://github.com/qingtan-labs/deepseek-harness-windows)

A native, one-click Windows controller for DeepSeek Harness. It installs an isolated verified runtime, reuses an existing browser tab by default, offers an optional WebView2 in-app window, and exposes service, update, and sign-in controls from the system tray.

- **Highlights:** One-click setup, browser-tab reuse, optional in-app window, system tray controls, explicit update checks, launch at sign-in, English and Simplified Chinese, and x64/ARM64 support
- **Requirements:** Windows 10 22H2 or Windows 11, x64 or ARM64, and .NET Framework 4.8
- **License:** MIT
- **Project status:** Independent community project; not affiliated with or endorsed by DeepSeek
- **Installation:** The default per-user installation requires no administrator privileges; release downloads include SHA-256 verification
- **Release trust:** The current release is not Authenticode-signed, so Windows SmartScreen may show an unknown-publisher warning
- **Links:** [Latest release and download](https://github.com/qingtan-labs/deepseek-harness-windows/releases/latest) · [Source code](https://github.com/qingtan-labs/deepseek-harness-windows) · [Installation guide](https://github.com/qingtan-labs/deepseek-harness-windows/blob/main/docs/installation.md) · [Security](https://github.com/qingtan-labs/deepseek-harness-windows/blob/main/SECURITY.md) · [简体中文](https://github.com/qingtan-labs/deepseek-harness-windows/blob/main/README.zh-Hans.md)

## Chrome Extensions

### [LoginFlip](https://qingtan-labs.github.io/loginflip/)

A privacy-first Chrome extension for saving local website login-state snapshots and switching between work, test, client, creator, and personal accounts in seconds.

- **Highlights:** One-click account switching, per-site account groups, shortcuts, pinned and ordered accounts, local-only storage, password-encrypted backups, recovery controls, System/Light/Dark themes, and English/Simplified Chinese
- **Privacy:** No LoginFlip account, developer server, cloud sync, telemetry, advertising, or tracking; session snapshots remain in Chrome on the user's device
- **Requirements:** Chrome 132 or later on macOS or Windows
- **Release:** Version 1.0.0, available worldwide for free
- **Official links:** [Install from the Chrome Web Store](https://chromewebstore.google.com/detail/mmkolcfdcgnimofbjjnkmmehnhmmonok) · [Product website](https://qingtan-labs.github.io/loginflip/) · [Privacy policy](https://qingtan-labs.github.io/loginflip/privacy/) · [Support](https://qingtan-labs.github.io/loginflip/support/)

The extension source and release engineering remain private personal assets; this showcase links only to public product materials and distribution channels.
