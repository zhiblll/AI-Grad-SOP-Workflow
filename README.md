# AI-Grad-SOP-Workflow
An AI-assisted workflow for writing and customizing SOPs for graduate programs.
一个用于美国研究生申请的 AI 辅助 SOP 工作流。

这个项目整理了我在研究生申请过程中实际使用的LLM写作方法：不是让LLM直接生成文书，而是先分析申请者的简历、成绩单、科研经历和个人叙述，通过多轮对话挖掘值得写入 SOP 的内容，再生成初稿并进行学校定制。

## 项目内容

- `prompts/`：适用于 ChatGPT、Claude、Gemini 等普通 LLM 的 Prompt 版本
- `skills/`：适用于 Codex、Claude Code 等 Agent 环境的 Skill 版本

目前主要包含：

- SOP 第一版开发：材料分析、经历挖掘、多轮访谈、叙事构建
- SOP 学校定制：根据目标项目要求对已有 SOP 进行分析和调整

## 核心理念

AI 在这个工作流中不是代写者，而是：

> 招生官视角的分析者、访谈者、故事挖掘者、批评者和写作协作者。

所有经历、动机和研究兴趣都应来自申请者本人，最终文书也应由申请者自行检查和修改。

## 使用方式

普通用户可以直接复制 `prompts/` 中的 Markdown 内容到常用 LLM 中使用。

如果使用支持 Skill 的 Agent，可以将 `skills/` 中对应的 Skill 安装到 Agent 环境中。
