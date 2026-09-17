<h1 align="center">GitHub README Design</h1>

<p align="center"><strong>为工具、应用和 Skill 编写、排版和更新 GitHub README。</strong></p>
<p align="center">
  <a href="https://github.com/AidenXu-1/github-readme-design/releases/latest">下载 Skill</a> ·
  <a href="#开始使用">开始使用</a> ·
  <a href="https://github.com/AidenXu-1/github-readme-design/issues">问题反馈</a>
</p>

## 能做什么

提供项目文件夹或 GitHub 链接，AI 会阅读项目，整理用途、功能、安装和使用说明，再完成 README 排版。可以从头写，也可以只改指定部分，保留原有风格。

图片优先使用项目已有的 Logo、界面和作品。有多张可选时，挑能看出实际效果的内容页。没有合适图片，就用文字排版；新增 Logo 或宣传图需明确提出。

## 开始使用

需要支持 Agent Skills、能读写项目文件的 AI 工具。读取 GitHub 仓库需要联网；Skill 本身无需额外安装运行程序。

### 1. 安装

从[发布页](https://github.com/AidenXu-1/github-readme-design/releases/latest)下载 `github-readme-design-v1.1.0.zip`，解压后将整个 `github-readme-design` 文件夹放入 AI 工具的 Skills 目录。

Codex 的安装位置：

```text
~/.codex/skills/github-readme-design/SKILL.md
```

### 2. 提供项目

附上仓库链接或本地项目文件夹，告诉 AI：

```text
使用 github-readme-design，重写这个项目的中文 README。
讲清用途和使用方法，优先用已有素材。
文案简洁，排版好看，先给我草稿。
```

只改一部分时，可以说：“更新安装说明，其他内容不动。”

### 3. 查看草稿

草稿保存在项目的 `README.draft.md`，新增图片会一并保存。有预览工具时，AI 会检查排版；查不清的信息会单独列出。

查看后可以继续修改。确认采用时，再要求替换正式 README 或推送到 GitHub。

## 规则说明

[工作规则](SKILL.md) · [页面组织](references/page-guide.md) · [视觉与成本](references/visual-guide.md)
