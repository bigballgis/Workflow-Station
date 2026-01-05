按 Kiro Specs 模式开发【功能名称】，例如：按 Kiro Specs 模式开发用户登录模块


ESLint/Prettier	强制编码规范，与 Spec 设计一致	项目根目录添加 .eslintrc.js、.prettierrc，配置与 design.md 中的规范匹配
CodeLens	显示代码与 Spec 文档的关联	安装 CodeLens 扩展，在注释中添加「关联需求：#1」「关联设计：API-001」
Git Hooks	提交前校验 Spec 文档是否更新	使用 husky 配置 pre-commit 钩子，检查 requirements.md、design.md 是否与代码同步
Copilot Workspace	增强任务拆解与 PR 生成	启用 Copilot Workspace，将 tasks.md 与 Issue/PR 关联，自动生成实现计划