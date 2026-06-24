# Wenzi 的日志

这是一个面向 GitHub Pages 的 Jekyll 博客骨架，用来记录日常、阅读、代码和想法。

## 写新日志

在 `_posts/` 目录中新建 Markdown 文件，文件名使用：

```text
YYYY-MM-DD-title.md
```

文件头部示例：

```yaml
---
title: "今天的标题"
date: 2026-06-25 21:30:00 +0800
tags: [生活, 读书]
excerpt: "一句话摘要。"
---
```

正文直接写 Markdown。

## 部署

推送到 `main` 分支后，仓库里的 GitHub Actions 会构建并发布 GitHub Pages。第一次使用时，在 GitHub 仓库的 `Settings -> Pages` 中把发布来源选择为 `GitHub Actions`。

项目页地址预设为：

```text
https://wenzi03.github.io/blog/
```

## 字体

字体文件已经验证为有效 WOFF2，并按内部字体名重命名：

- `assets/fonts/anthropic-sans-web-text.woff2`
- `assets/fonts/anthropic-serif-web-text.woff2`
