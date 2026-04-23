# implement-design-skill

面向 AI 助手的 **「实现设计」** 技能：将设计稿、标注或视觉规格转译为可上线的应用代码，并坚持高保真视觉还原。技能说明与 Ardot MCP 用法均写在同一份文档中。

## 它解决什么问题

- 在交付物是**用户仓库中的前端代码**时，用固定步骤收齐设计上下文、建立验收基准、落盘资源、对齐本仓库技术栈，最后对照设计做校验。
- 设计来源可包括：腾讯设计 [Ardot](https://docs.ardot.tencent.com/ardot-mcp.html)（含 MCP）、蓝湖 / MasterGo / Pixso 等协作平台、静态导出图、或文档 + 截图组合。

不适用于：只在设计工具里改稿、或「从代码反推设计」——应使用对应设计工具或团队专用能力。

## 仓库结构

```
skills/implement-design/SKILL.md   # 完整技能：工作流、规则、Ardot MCP 附录
```

## 如何使用

1. 将本仓库中的 `skills/implement-design/` 安装到你的 Agent 技能目录（具体路径依所用客户端而定，例如 Cursor 的 `skills` 或 `.cursor/skills` 等约定）。
2. 在助手中开启该技能后，在需要「按稿开发」「还原 UI」「高保真实现设计」时，助手会按 `SKILL.md` 中的必选工作流执行。

更细的边界、步骤清单与 Ardot 工具推荐调用顺序，请直接阅读 [skills/implement-design/SKILL.md](skills/implement-design/SKILL.md)。

## 相关链接

- [Ardot MCP Server 简介](https://docs.ardot.tencent.com/ardot-mcp.html)（工具与常见问题以官方为准）
