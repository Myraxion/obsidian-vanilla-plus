# Agent 行为准则 (Obsidian 开发)

- **官方文档优先**：涉及 Obsidian 样式、配置与插件开发时，优先使用 Context7 检索官方开发者文档（`/obsidianmd/obsidian-developer-docs`）。
- **原生底层实现**：全面优先采用官方底层变量与标准规范（如 `--h*-color`、`--link-external-*`、`--bold-modifier` 等），禁止脱离原生变量重复造轮子。
- **拒绝过度防御**：恪守 KISS 原则，去除冗余的 DOM 深度嵌套选择器、`!important` 及对第三方插件的非必要防御，保持代码最简、透明且易于维护。
