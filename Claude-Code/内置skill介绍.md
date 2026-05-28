# Claude Code 内置 Skill 介绍

## 什么是 Skill？

Skill 是 Claude Code 的扩展包，能给 Claude 添加特定领域的知识和能力。安装后，Claude 在遇到相关任务时会自动调用对应的 skill。

## 已安装的 Skill

| Skill | 安装来源 | 作用 |
|-------|---------|------|
| `find-skills` | 系统自带 | 搜索和发现可安装的 skill |
| `brainstorm` | buiducnhat/agent-skills | 在需求模糊时理清思路、探索方案 |
| `plan-writing` | davila7/claude-code-templates | 把任务拆解成可执行的小步骤 |
| `using-agent-skills` | addyosmani/agent-skills | 发现和调用其他 skill 的元技能 |

## Claude Code 自带 Skill（无需安装）

| Skill | 作用 |
|-------|------|
| `code-review` | 审查代码改动，发现 bug 和改进点 |
| `verify` | 运行项目验证变更是否生效 |
| `simplify` | 自动审查并应用改进 |
| `security-review` | 安全审查 |
| `init` | 初始化 CLAUDE.md 项目文档 |
| `run` | 启动和运行项目 |
| `loop` | 定时重复执行任务 |
| `update-config` | 修改 settings.json 配置 |
| `keybindings-help` | 自定义键盘快捷键 |

## 常用命令

| 命令 | 说明 |
|------|------|
| `npx skills find <关键词>` | 搜索 skill |
| `npx skills add <包名> -g -y` | 全局安装 skill |
| `npx skills list -g` | 查看已安装的全局 skill |
| `npx skills update` | 更新所有 skill |
