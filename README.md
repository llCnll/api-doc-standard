# api-doc-standard

用于编写和审查中文 API 文档的 Codex Skill，按业务功能组织页面，而不是按单个路由拆分。

一个功能页面可以包含多个相关路由。各路由分别说明请求与响应；共享规则、枚举、取值来源、验证说明和示例集中在同一功能页面中。

## 使用

编写、整理或审查 API 文档时调用 `$api-doc-standard`。

## 内容

- `SKILL.md`：技能说明与使用指引
- `references/feature-page-template.md`：功能页面模板
- `agents/openai.yaml`：Codex 界面元数据
