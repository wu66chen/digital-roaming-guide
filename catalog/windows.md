# Windows · 软件收藏

> 用于找回已经验证好用的 Windows 工具。**“新系统必装”是个人恢复优先级，不代表所有人都需要。**

[← 返回指南首页](../README.md) · [Windows 重装清单](../reinstall/windows.md) · [跨平台工具](cross-platform.md)

## 新系统必装 · Essentials

| 软件 | 核心用途 | 我为什么保留 | 官方获取 | 状态 |
| --- | --- | --- | --- | --- |
| **7-Zip** | 压缩与解压 7z、ZIP、RAR 等格式 | 稳定、轻量，基础文件处理离不开 | [官网](https://www.7-zip.org/) | 必装 |
| **PotPlayer** | 本地视频与音频播放 | 格式兼容性强，便于管理本地视频播放 | [官网](https://potplayer.daum.net/) | 必装 |
| **QuickLook** | 资源管理器中按空格快速预览文件 | 不打开大型应用就能快速查看文件 | [项目 / Releases](https://github.com/QL-Win/QuickLook) | 必装 |
| **Geek Uninstaller** | 卸载应用、查找相关残留 | 便携、操作直接，适合清理试用程序 | [官网下载](https://geekuninstaller.com/download) | 必装 |

## 已验证好用 · 按需安装

| 软件 | 什么时候需要 | 为什么保留 | 官方获取 | 状态 |
| --- | --- | --- | --- | --- |
| **File Converter** | 文件右键格式转换、压缩 | 直接在资源管理器操作，减少打开独立转换软件的次数 | [官网](https://file-converter.io/) / [源码](https://github.com/Tichau/FileConverter) | 按需 |
| **Rufus** | 重装系统、制作 Windows / Linux 启动 U 盘 | 体积小、无需复杂安装，重装时非常实用 | [官网](https://rufus.ie/) | 按需 |
| **ComfyUI Portable** | 本地 AI 图像工作流、放大与节点处理 | 可在浏览器使用，模型和工作流更易集中管理 | [官方项目及发布](https://github.com/Comfy-Org/ComfyUI/releases) | 按需 |

### ComfyUI 安装备注

- 使用的是 **Windows Portable / Standalone（`ComfyUI_windows_portable`）**，自带 `python_embeded`，启动本地 Web 页面；**不是 ComfyUI Desktop**。
- 过往使用过带 `--windows-standalone-build`、`--listen`、`--enable-manager` 的启动方式。
- 旧使用记录出现过 `0.39.0`，但具体下载包的完整名称、CUDA 构建和当前安装版本尚未核定；重装时应根据显卡和官方 Releases 重新选择。
- 自己使用的模型、工作流、custom nodes 配置要独立备份。不要为了记录工具在公开仓库发布个人路径、访问令牌或 NAS 信息。

## 也支持 Windows 的跨平台工具

[Bitwarden（必装）](cross-platform.md#跨平台必装--essential) · [PixPin、Keyviz、Tailscale（按需）](cross-platform.md#跨平台已验证好用--on-demand)

> 优先记录作用与官方来源，不追踪短期软件版本号。
