# One

<p align="center">
  <img src="docs/screenshots/main-light.png" width="648" alt="One main panel">
</p>

<p align="center">
  <b>A small menu bar app for macOS.</b><br>
  Network latency · power · processes · cleanup · uninstall<br>
  macOS 菜单栏小工具：网络延迟、功耗、进程、清理与卸载。
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Download-One%201.3-2ea44f?style=for-the-badge" alt="Download One"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-14%2B-lightgrey" alt="macOS 14+">
  <img src="https://img.shields.io/badge/Apple%20Silicon-arm64-orange" alt="Apple Silicon">
  <img src="https://img.shields.io/badge/version-1.3%20(build%205)-blue" alt="Version 1.3 build 5">
</p>

**English** | [中文](#中文)

---

## English

One keeps network latency, power, running apps and cleanup in one menu bar panel. It can also uninstall apps with their related files.

### Features

- **Network latency** — check common sites or any host, and retest with one click.
- **Power** — whole-machine power, CPU, GPU, fan and memory.
- **Processes** — apps ranked by CPU, memory or energy; expand and end processes.
- **Cleanup** — scan, review, and move selected items to the Trash.
- **Uninstall** — drop in an app to see and remove its related files.
- **Menu bar only** — light and dark appearance, all data stays on your Mac.

### Screenshots

<p align="center">
  <img src="docs/screenshots/main-light.png" width="648" alt="Main panel in light mode">
</p>

| Cleanup | Power |
| --- | --- |
| <img src="docs/screenshots/cleanup-light.png" width="330" alt="Cleanup scan"> | <img src="docs/screenshots/power-light.png" width="330" alt="Power detail"> |
| **Permissions** | **Uninstall** |
| <img src="docs/screenshots/permissions-light.png" width="330" alt="Permission notice"> | <img src="docs/screenshots/uninstall-light.png" width="260" alt="Uninstall preview"> |

<p align="center">
  <img src="docs/screenshots/main-dark.png" width="648" alt="Main panel in dark mode">
</p>

### Install

1. Download **One-1.3.dmg** from [Releases](../../releases/latest).
2. Open the DMG and drag **One** into **Applications**.
3. On first launch, right-click **One** and choose **Open** (ad-hoc signed, not notarized).
4. Click the **One** icon in the menu bar.

If macOS still blocks it: `xattr -dr com.apple.quarantine /Applications/One.app`

**Requirements:** macOS 14+, Apple Silicon, about 2 MB.

### Permissions

Downloads (file sizes for cleanup) and Local Network (network and proxy state). No Full Disk Access, admin password, Screen Recording or Accessibility; no analytics, no uploads.

### Uninstall

Quit One from the menu bar, drag **One.app** to the Trash. If **Launch at Login** is on, remove `~/Library/LaunchAgents/com.yimo.one.plist`.

### Credits

Power sampling uses [macmon](https://github.com/vladkens/macmon) by vladkens (MIT).

---

## 中文

One 把网络延迟、功耗、运行中的应用和清理放在一个菜单栏面板里，也能卸载应用和它的关联文件。

### 功能

- **网络延迟**：检测常用站点或任意地址，一键重测。
- **功耗**：整机功耗、CPU、GPU、风扇和内存。
- **进程**：按 CPU、内存或能耗查看应用，可展开、可结束。
- **清理**：扫描、勾选，移入废纸篓。
- **卸载**：拖入应用，查看并移除关联文件。
- **菜单栏应用**：深浅色跟随系统，所有数据留在本机。

### 截图

截图与英文部分共用，见上方 [Screenshots](#screenshots)。

### 安装

1. 从 [Releases](../../releases/latest) 下载 **One-1.3.dmg**。
2. 打开 DMG，把 **One** 拖进 **应用程序**。
3. 第一次打开：右键 **One**，选择「打开」（ad-hoc 签名，没有公证）。
4. 点击菜单栏的 **One** 图标。

如果系统仍然拦截：`xattr -dr com.apple.quarantine /Applications/One.app`

**系统要求：** macOS 14+，Apple Silicon，约 2 MB。

### 权限

下载文件夹（统计清理所需文件大小）和本地网络（网络与代理状态）。不申请完全磁盘访问、管理员密码、屏幕录制或辅助功能权限；没有统计和遥测，不上传数据。

### 卸载

从菜单栏退出 One，把 **One.app** 拖进废纸篓。如果开过「登录时自动启动」，删除 `~/Library/LaunchAgents/com.yimo.one.plist`。

### 致谢

功耗采样使用 [macmon](https://github.com/vladkens/macmon)（作者 vladkens，MIT 许可）。
