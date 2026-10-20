---
slug: zh-cn/real-world-development/cli
title: "GitHub Copilot CLI"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** 将 GitHub Copilot 作为代理式编码助手带入终端。它可以探索代码库、生成代码、运行命令，并连接外部工具——全部通过命令行完成，无需切换到图形化编辑器即可保持工作流畅。

本工作坊将围绕 Tailspin Toys 的完整工作流程展开：在 GitHub Codespaces 中准备项目，添加星级评分，然后从 issue 开始实现筛选功能。你将使用 Plan 模式确定方案，通过 Autopilot 实现，并在 Interactive 模式中审查。还会更新存储库说明、自定义 `quality-checks` 技能、使用 Playwright MCP 验证筛选功能、创建 QA 自定义智能体并审查最终 PR。为聚焦工作坊内容，将创建两个 PR：一个用于星级评分，另一个用于筛选及相关质量工作。还可以学习[使用 GitHub Copilot CLI 和 Foundry 的可选系列课程][foundry]，通过三个模块准备模型、构建并部署托管智能体，以及将其集成到网站中。

## 练习

| 练习 | 主题 | 说明 |
|----------|-------|-------------|
| [0. 先决条件][ex0] | 设置 | 创建存储库和 codespace |
| [1. 安装 Copilot CLI][ex1] | 安装 | 安装并验证 Copilot CLI |
| [2. 添加星级评分][ex2] | 首次更改 | 显示现有评分并合并第一个 PR |
| [3. 智能体模式：Plan 和 Autopilot][ex3] | 智能体模式 | 从 issue 规划功能、实现并审查 |
| [4. 使用自定义说明引导 Copilot][ex4] | 上下文 | 更新说明并将其应用于筛选功能 |
| [5. 自定义并使用质量检查技能][ex5] | 可重复检查 | 自定义现有技能并运行检查 |
| [6. 使用 Playwright MCP 验证功能][ex6] | 浏览器观察 | 配置 MCP 并检查浏览器中的筛选行为 |
| [7. 创建并使用 QA 智能体][ex7] | 需求与覆盖范围 | 检查需求、覆盖范围和验证证据 |
| [8. 创建并合并功能 PR][ex8] | 审查与合并 | 审查完整更改并使用 Agent Merge |
| [9. GitHub Copilot CLI 斜杠命令][ex9] | CLI 功能 | 探索上下文、模型和共享 |
| [10. 回顾与后续步骤][ex10] | 总结 | 回顾工作流程和更多资源 |
| [可选：集成 Foundry][foundry] | 托管智能体 | 准备模型、部署基于目录的智能体并将其连接到网站 |

## 先决条件

参加本工作坊前，请确保已具备以下条件：

- [ ] 拥有 GitHub 账户，并已启用 **Copilot Student、Pro、Pro+、Business 或 Enterprise** 计划
- [ ] 对终端/命令行操作有基本了解
- [ ] 已安装并配置 Git

> [!TIP]
> 没有付费计划？已验证学生可通过 [GitHub Education][callout-student-plan-education] 免费使用 GitHub Copilot。**Copilot Student** 计划包含本工作坊所用的智能体、MCP、代码审查和 Copilot CLI 功能，因此可以完整完成所有路径。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> 如果使用的是 Copilot Business 或 Copilot Enterprise，请确认管理员已启用 Copilot CLI。

## 开始

**[从练习 0：先决条件开始 →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
[foundry]: 8-foundry-agent/
