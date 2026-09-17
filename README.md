<div align="center">

# GitHub README Design

**把工具和 Skill 的 GitHub 首页写清楚、排好看，让访客顺利开始使用。**

通用 Agent Skill · 新建 README · 整体装修 · 局部更新

[下载安装](https://github.com/AidenXu-1/github-readme-design/releases/latest) · [使用流程](#使用流程) · [问题反馈](https://github.com/AidenXu-1/github-readme-design/issues)

</div>

## 它会帮你做什么

提供项目文件夹或 GitHub 仓库链接，Agent 会阅读项目，编写面向使用者的 README。

| 首页部分 | 读者能看懂什么 |
| --- | --- |
| 名称、简介与主要入口 | 项目有什么用，从哪里开始 |
| 截图、演示或输入输出示例 | 实际效果是什么样 |
| 安装与使用步骤 | 准备什么、怎么操作、会得到什么 |
| 文档、反馈与许可 | 遇到问题去哪里找帮助 |

章节按项目需要取舍。已有 README 时，可以保留原有风格，只更新指定内容。

## 使用条件

一个能读取 Skill 和项目文件、编写 Markdown 的通用 Agent。提供 GitHub 链接时需要联网读取仓库；检查页面显示时使用当前环境可用的预览工具。

Skill 本身只有规则与页面指南，无需安装专用生成程序或 Python 环境。

## 安装

1. 从[发布页](https://github.com/AidenXu-1/github-readme-design/releases/latest)下载 `github-readme-design-v1.0.0.zip`。
2. 解压，将整个 `github-readme-design` 文件夹添加到 Agent 的 Skill 目录。

以 Codex 为例：放入 `~/.codex/skills/`，最终路径为 `~/.codex/skills/github-readme-design/SKILL.md`。其他 Agent 按其 Skill 安装方式添加。

## 使用流程

**提供项目 → 理解用途与使用方式 → 编写并排版 → 核对内容与显示 → 交付草稿**

### 1. 提供项目和要求

示例请求：

> 使用 GitHub README Design，为这个仓库制作中文 README。
> 重点展示用途、效果和安装使用流程，先交付草稿。
> 仓库地址：附上你的 GitHub 链接。

也可以提供本地文件夹，或指定“只更新安装说明，保留其余内容”。在 Codex 中可用 `$github-readme-design` 调用。

### 2. 阅读并编写

Agent 会查看已有说明、安装入口和展示素材，再组织内容。正式选项与操作名称保持准确，解释用短句；不会把某个平台的安装示例写成产品的全部适用范围。

缺失的关键信息会向你确认。没有截图、许可或性能依据时，不编造内容，也不保留无意义的空章节。

### 3. 查看草稿

默认得到项目目录中的 `README.draft.md`，以及本次检查结果和需补充的信息。能预览时，会检查页面显示。

确认内容后，可以继续要求调整，或明确让 Agent 替换正式 README、推送到 GitHub。仅要求草稿时不会改动线上仓库。

## 设计原则

- **按真实项目写**：用途、功能、选项和安装步骤有依据。
- **读者能照着用**：写清输入、操作与结果。
- **同一信息讲一次**：FAQ 只补充正文没有回答的问题。
- **按需读取**：主规则负责工作边界，页面指南在编写时读取。

## 反馈与参考

[提交问题](https://github.com/AidenXu-1/github-readme-design/issues) · [主规则](SKILL.md) · [页面组织指南](references/page-guide.md)
