# YoYo Design System Skill

YoYo 产品设计系统技能文件，供 AI 助手（Claude Code / Cursor 等）在 Figma 中直接构建符合 YoYo 设计规范的移动端页面。

## 使用方式

将 `SKILL.md` 放入 AI 助手的 commands 目录中，通过 `/yoyo-design` 调用。

## 核心能力

- **查询规范**：配色、字号、间距、按钮样式等
- **组件推荐**：根据场景推荐 YoYo 组件库中的已有组件
- **Figma 原生构建**：通过 Figma Plugin API 直接在画布中创建页面，自动导入组件库组件
- **设计走查**：检查设计是否符合规范

## 工作流

1. 用户描述需求（如 "构建一个评价页"）
2. AI 自动加载 `/figma-use` 技能
3. AI 从 YoYo 组件库导入匹配组件（nav bar、bottom bar、buttons 等）
4. AI 在 Figma 画布中逐步构建页面内容
5. 通过截图验证，发现问题立即修复

## 组件库

- **Figma 文件**：[YoYo_library](https://www.figma.com/design/GxW7MR9p08qbqCPt5Tzrjw/YoYo_library)
- 包含：Bars、Icons、Buttons、Sheets、Cards、Tabs、Lists、Badges & Tags、Feeds

## 规则

- 所有 UI 文字使用**英文**
- **组件库优先**：禁止手动重建已有组件
- 输出必须是**生产级**效果，禁止灰色占位方块

## 详细规范

完整设计规范见 [SKILL.md](./SKILL.md)
