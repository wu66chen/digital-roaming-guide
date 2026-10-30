# macOS｜常用终端命令

## Gatekeeper：查看应用安全检查状态

**用途：** 查看系统应用安全评估是否启用。

```bash
spctl --status
```

**结果：** `assessments enabled` 为启用；`assessments disabled` 为停用。具体行为可能受系统版本和配置影响。

## Gatekeeper：恢复默认安全评估

**用途：** 曾全局关闭评估后，尝试重新启用。

```bash
sudo spctl --master-enable
```

**影响：** 修改系统级应用安全评估配置，需要管理员权限。完成后在「系统设置 → 隐私与安全性」核对。

## Gatekeeper：旧有的全局停用命令

**用途：** 记录历史上用于关闭应用安全评估的命令。**有安全风险；不作为常规软件安装步骤。**

```bash
sudo spctl --master-disable
```

**注意：** 在较新 macOS 中，命令是否可用及后续确认方式可能不同。建议按单个 App 使用「仍要打开」，并先排除安装包损坏或恶意软件。

**相关指南：** [macOS 应用无法打开](../guides/macos/app-security-alerts.md)

**参考：** [Apple 官方说明](https://support.apple.com/zh-cn/102445) · [Apple 开发文档](https://help.apple.com/xcode/mac/current/en.lproj/dev9b7736b0e.html)
