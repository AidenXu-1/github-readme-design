<h1 align="center">GitHub README Design</h1>

<p align="center"><strong>把项目的用途、效果和使用方法，排成一页好看的 GitHub 主页。</strong></p>
<p align="center">工具 · 应用 · Agent Skill</p>
<p align="center">
  <a href="https://github.com/AidenXu-1/github-readme-design/releases/latest">下载 Skill</a> ·
  <a href="#开始使用">开始使用</a> ·
  <a href="https://github.com/AidenXu-1/github-readme-design/issues">问题反馈</a>
</p>

## 交给它什么，会得到什么

提供本地项目文件夹或 GitHub 仓库链接，再说清楚想新写、整体装修，还是只改一部分。

| 你提供 | 它交付 |
| --- | --- |
| 项目文件或仓库链接 | 按真实功能组织的 README 草稿 |
| 已有 Logo、界面、宣传图或作品（如有） | 精选素材与适合 GitHub 的图文排版 |
| 语言、风格和本次修改范围 | 可打开的文件、检查结果与仍需补充的信息 |

有图片时，优先展示核心界面和完整内容页；没有合适图片时，用文字层级与留白组织页面。不会自行补造 Logo、宣传图或产品界面。需要新增品牌视觉时，可以明确提出。

## 开始使用

需要一个支持 Agent Skills、能够读写项目文件的 AI 工具。读取在线仓库需要联网，查看排版需要可用的预览工具。Skill 本身无需额外安装生成程序。

### 1. 安装

从[最新发布页](https://github.com/AidenXu-1/github-readme-design/releases/latest)下载 `github-readme-design-v1.1.0.zip`，解压后把完整的 `github-readme-design` 文件夹放入 Agent 的 Skills 目录。

以 Codex 为例，安装后的入口为：

```text
~/.codex/skills/github-readme-design/SKILL.md
```

其他 Agent 按各自的 Skill 安装方式添加。

### 2. 提供项目

附上仓库链接或本地项目文件夹，再告诉 AI：

```text
使用 github-readme-design，为这个项目装修中文 README。
先展示用途和实际效果，再写安装与首次使用。
优先复用已有素材，文案简洁。
先交付 README.draft.md，供我查看。
```

局部更新也可以直接说：“只更新安装说明，保留其他内容和现有风格。”

### 3. 查看并采用

默认在目标项目中生成 `README.draft.md`，需要新增素材时一并交付。能预览时会检查显示，并说明尚未核实的内容。

查看后继续提出修改，或明确要求替换正式 README、推送到 GitHub。只要草稿时，不改动线上仓库。

## 页面怎么取舍

- **先看懂，再开始**：用途、实际效果、安装与使用依次展开，章节按项目需要取舍。
- **素材用在关键处**：复用真实内容，集中展示一个有代表性的结果，减少制作和维护成本。
- **同一信息说一次**：删掉重复小字，保留影响使用的限制和必要来源。
- **事实有依据**：安装入口、功能和许可按项目核对，不编造数据或实测结果。

[工作规则](SKILL.md) · [页面组织](references/page-guide.md) · [视觉与成本](references/visual-guide.md)
