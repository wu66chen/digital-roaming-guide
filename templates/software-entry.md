# 软件条目模板

[首页](../README.md)

## 目录表格格式

将新软件添加到所属 `catalog/*.md` 的分类表格中：

```markdown
| 软件 | 用途 | 官网 | GitHub | 我的使用体验 |
| --- | --- | --- | --- | --- |
| **软件名称** | 一句话说明用途 | [官网](https://example.com) | [GitHub](https://github.com/example/project) | *待填写* |
```

- 无官网或 GitHub 时填写 `-`。
- 浏览器扩展、用户脚本可增加「安装 / 发布页」列。
- 「我的使用体验」优先写一句个人评价，保持表格易读。

## 详细使用体验（可选）

如果需要记录更多内容，在该分类表格下方加入以下折叠区：

```markdown
<details>
<summary><b>软件名称 · 详细使用体验</b></summary>

**主要使用场景**

待填写

**喜欢的地方**

待填写

**不足之处**

待填写

</details>
```

详细体验不必每个软件都创建。仅在需要时添加。

## 重装清单格式

```markdown
- [ ] **软件名称** — [官网](https://example.com) · [GitHub](https://github.com/example/project) · 体验：*待填写*
```
