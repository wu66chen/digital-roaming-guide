# macOS 新设备软件清单 · Mac Setup

[← 返回指南首页](../README.md) · [macOS 收藏详情](../catalog/macos.md) · [清理工具对比](../guides/macos-cleaners.md)

> 下面的“必装”是当前个人恢复清单，并不要求所有工具一直后台运行。

## 核心长期安装

| 软件 | 为什么保留 | 官方来源 | 备注 |
| --- | --- | --- | --- |
| [Pastel](https://github.com/EEliberto/Pastel-macOS) | 获取旧版 iOS App IPA | [GitHub](https://github.com/EEliberto/Pastel-macOS) | 官方要求 Apple Silicon / macOS 26+ |
| wifi-loc-control | 自动切换网络环境配置 | 私人工具，无公开下载页 | 重装前做好私人备份，勿公开规则 |
| [NewFile](https://github.com/mariusgm/newfile) | Finder 新建文件 | [项目（待核对具体同名软件）](https://github.com/mariusgm/newfile) | 初次需开启 Finder 扩展 |
| [AppCleaner](https://freemacsoft.net/appcleaner/) | 卸载应用及关联文件 | [官网](https://freemacsoft.net/appcleaner/) | 以实际卸载需求启动 |
| [PureMac](https://github.com/momenbasel/PureMac) | 图形化存储和清理检查 | [GitHub](https://github.com/momenbasel/PureMac) | 不建议立即启用自动清理 |
| [Mole CLI](https://github.com/tw93/Mole) | 高级清理 / 路径分析 | [GitHub](https://github.com/tw93/Mole) | `brew install mole` 是命令行版本 |
| [Mos](https://github.com/Caldis/Mos) | 鼠标滚轮优化 | [GitHub](https://github.com/Caldis/Mos) | 按需授予辅助功能权限 |
| [Bitwarden](https://bitwarden.com/download/) | 密码管理 | [官网下载](https://bitwarden.com/download/) | 跨平台必装 |

## 已验证跨平台按需工具

| 软件 | 需要时再装 | 官方来源 |
| --- | --- | --- |
| [PixPin](https://pixpin.cn/) | 截图、OCR、长截图 | [官网](https://pixpin.cn/) |
| [Keyviz](https://github.com/mulaRahul/keyviz) | 教程录制时显示键鼠操作 | [GitHub](https://github.com/mulaRahul/keyviz) |
| [Tailscale](https://tailscale.com/download) | 远程连接个人设备 | [官网](https://tailscale.com/download) |

## 不再安装

| 软件 | 原因 | 替代 |
| --- | --- | --- |
| *待整理* | — | — |

## 迁移提醒

- [AppCleaner / PureMac / Mole 区别和使用边界](../guides/macos-cleaners.md)。
- 个人网络脚本备份和配置应保存在私人空间，不要直接提交到公开 GitHub。
- Finder 扩展、辅助功能、输入监控等系统权限换设备后需要重新授权。
