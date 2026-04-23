# implement-design-skill

面向 AI 助手的 **「实现设计」** 技能：将设计稿、标注或视觉规格转译为可上线的应用代码，并坚持高保真视觉还原。技能说明与 Ardot MCP 用法均写在同一份文档中。

## 它解决什么问题

- 在交付物是**用户仓库中的前端代码**时，用固定步骤收齐设计上下文、建立验收基准、落盘资源、对齐本仓库技术栈，最后对照设计做校验。
- 设计来源可包括：腾讯设计 [Ardot](https://docs.ardot.tencent.com/ardot-mcp.html)（含 MCP）、蓝湖 / MasterGo / Pixso 等协作平台、静态导出图、或文档 + 截图组合。

## 仓库结构

```
skills/implement-design/SKILL.md   # 完整技能：工作流、规则、Ardot MCP 附录
```

## 安装

使用 [skills 生态 CLI](https://github.com/vercel-labs/skills)（会安装到本机已检测到的 Agent，例如 Cursor、Claude Code、Codex 等）：

```bash
npx skills add guangzan/implement-design-skill
```

## 如何使用

1. **推荐：** 使用上文「安装」中的 `npx skills add`；或手动将 `skills/implement-design/` 复制/链接到你的 Agent 技能目录（路径依客户端而定，例如 Cursor 的 `.cursor/skills` 等约定）。
2. 开启该技能后，在需要「按稿开发」「还原 UI」「高保真实现设计」时，助手会按 `SKILL.md` 中的必选工作流执行。

更细的边界、步骤清单与 Ardot 工具推荐调用顺序，请直接阅读 [skills/implement-design/SKILL.md](skills/implement-design/SKILL.md)。

## 相关链接

- [Ardot MCP Server 简介](https://docs.ardot.tencent.com/ardot-mcp.html)（工具与常见问题以官方为准）
