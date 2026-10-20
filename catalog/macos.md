# macOS · 软件收藏

> 以真实体验形成的个人软件清单，便于更换 Mac 后快速恢复。以下「必装」沿用个人收藏分类；清理工具不意味着必须同时常驻或每天清理。

[← 返回指南首页](../README.md) · [macOS 迁移清单](../reinstall/macos.md) · [Mac 清理工具对比](../guides/macos-cleaners.md)

## 新系统必装 · Essentials

| 软件 | 解决什么问题 | 为什么留下 | 官方获取 | 状态 |
| --- | --- | --- | --- | --- |
| **Pastel** | 查询、下载 App Store 应用历史 IPA，并发送至 iPhone / iPad | 需要旧版 iOS App 时便于找回 | [GitHub](https://github.com/EEliberto/Pastel-macOS) / [Releases](https://github.com/EEliberto/Pastel-macOS/releases) | 必装 |
| **wifi-loc-control** | 按 Wi-Fi / 所在网络环境调整 Mac 网络配置 | 在不同网络之间切换时减少手动设置 | 本地自用脚本，公开下载地址暂缺 | 必装 · 私人工具 |
| **NewFile** | 给 Finder 添加创建新文件的功能 | 补足 Finder 默认文件操作中的缺口 | [NewFile 项目（待核对是否为所用版本）](https://github.com/mariusgm/newfile) | 必装 |
| **AppCleaner** | 卸载应用时查找关联文件 | 拖放卸载简单直接 | [官网](https://freemacsoft.net/appcleaner/) | 必装 |
| **PureMac** | 图形化清理缓存、应用残留、存储管理与系统检查 | 适合想查看分类和文件后再清理的情形 | [官方源码](https://github.com/momenbasel/PureMac) | 必装 |
| **Mole（CLI）** | 命令行深度清理、卸载、磁盘分析与维护 | 适合需要更细致检查的清理任务 | [官方项目](https://github.com/tw93/Mole) | 必装 |
| **Mos** | 鼠标滚轮平滑滚动与滚动方向自定义 | 改善外接鼠标在 macOS 的使用体验 | [官方项目](https://github.com/Caldis/Mos) | 必装 |

## 需要特别保留的设置

- **Pastel**：当前官方说明要求 Apple Silicon + macOS 26 或更高版本；涉及 Apple 账户登录，注意官方发布和账户安全。
- **wifi-loc-control**：这是个人网络环境切换脚本。需在私人备份里记录脚本、权限与网络规则；不要把 Wi-Fi 名称、代理、内网 IP 等私人配置直接公布到公共仓库。
- **NewFile**：同名软件较多，上述 GitHub 来源仍待与你实际安装的软件核对。
- **Mole**：`brew install mole` 安装的是**免费开源 CLI**；另有单独的原生 GUI 产品，不能混为一个安装包。

## 三款清理工具的角色

| 软件 | 最适合的工作 | 优势 | 主要限制 |
| --- | --- | --- | --- |
| **AppCleaner** | 单个 App 卸载与相关文件清理 | 操作简单、适合日常卸载 | 不负责广泛的磁盘分析和系统清理 |
| **PureMac** | 图形化总览、磁盘与缓存清理 | 面板直观、功能较完整 | 功能和 Mole 重叠；某些清理可永久删除文件 |
| **Mole CLI** | 命令行检查、批量清理、开发缓存 | 适合熟悉终端的复杂任务，支持预览及排除 | 误选目标仍有删除风险；需要理解指令 |

详细安全边界、优缺点与使用场景见 **[AppCleaner / PureMac / Mole 对比指南](../guides/macos-cleaners.md)**。

## 跨平台工具

[Bitwarden（必装）](cross-platform.md#跨平台必装--essential) · [PixPin、Keyviz、Tailscale（按需）](cross-platform.md#跨平台已验证好用--on-demand)

> “系统清理”不是日常维护 KPI。先确认空间确实不足或有明确卸载需求，再决定是否执行清理。
