# AI Project Requirements & Delivery Copilot｜ai-project-delivery-copilot

> 把 AI 项目目标拆成范围、故事、里程碑、责任、风险和验收闭环。

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![AI Agent Skill](https://img.shields.io/badge/AI-Agent%20Skill-blue)
![Language](https://img.shields.io/badge/language-中文-orange)

这是一个面向真实业务工作的开源 AI Agent Skill。它不是一组零散 Prompt，而是一套包含任务边界、执行流程、质量检查和交付模板的可复用方法，让支持 Markdown 指令的 AI 助手能够更稳定地完成 **AI Project Requirements & Delivery Copilot** 相关任务。

**English:** An open-source AI agent skill for ai project requirements & delivery copilot, built around practical workflows, reusable deliverables, quality checks, and human-review boundaries.

## 为什么这个技能有用

把 AI 项目目标拆成范围、故事、里程碑、责任、风险和验收闭环。技能强调可执行结果、明确假设和人工复核点，适合从一次性对话升级为可复用的团队工作流。

### 核心能力

- 业务目标、范围和变更边界
- 用户故事、工作包和依赖
- 里程碑、迭代批次与 RACI
- 风险、评测、成本、安全和回滚治理

### 你可以获得

- 项目范围与 WBS
- 迭代看板和里程碑
- RACI 与风险台账
- 发布验收和纠偏方案

## 适合谁

- AI 项目经理和交付负责人
- 产品、研发与业务协作团队
- 需要治理 AI 项目不确定性的组织

## 直接这样使用

将下面任一请求交给支持读取本地文件的 AI Agent：

> 把 AI 客服项目拆成 8 周里程碑、任务和验收标准
>
> 分析这个延期项目的依赖、风险与纠偏计划

Agent 应先读取 [SKILL.md](SKILL.md)，再按其中的流程和质量要求执行任务。

## 快速开始

~~~bash
git clone https://github.com/zchstime/ai-project-delivery-copilot.git
cd ai-project-delivery-copilot
~~~

然后对你的 AI 助手说：

~~~text
请读取 SKILL.md，并使用这个技能处理我的任务。开始前先确认目标、输入、限制和期望交付物。
~~~

不同 AI Agent 客户端的技能安装目录和触发机制可能不同；只要客户端能够读取 Markdown 文件，就可以直接引用本仓库中的 **SKILL.md**。

## 技能包内容

- [SKILL.md](SKILL.md)：技能定义、执行步骤与质量边界
- [output-template.md](references/output-template.md)
- [LICENSE](LICENSE)：MIT 开源许可证

## 设计原则

- **结果导向**：输出方案、模板、清单、指标或可执行下一步，而不止是泛泛建议。
- **证据与假设分离**：明确哪些是事实、推断和待验证信息。
- **人机协作**：对高风险判断保留人工复核、权限控制和撤销路径。
- **可复用与可验收**：让同类任务能够重复执行，并通过明确标准检查质量。

## 搜索关键词

<code>ai</code> · <code>ai-agent</code> · <code>agent-skills</code> · <code>prompt-engineering</code> · <code>open-source</code> · <code>ai-project-management</code> · <code>project-delivery</code> · <code>agile</code> · <code>risk-management</code> · <code>project-planning</code>

## 为什么值得 Star

如果你正在建设 AI Project Requirements & Delivery Copilot 相关的 AI 工作流，这个仓库可以作为可直接复用的起点，也适合作为团队内部 Prompt、SOP 和验收规范的共同底稿。**Star ⭐ 这个仓库，方便以后快速找到；也欢迎通过 Issue 或 Pull Request 分享真实案例和改进建议。**

## License

[MIT License](LICENSE) © 2026 珠海横琴来一桔文化科技有限公司
