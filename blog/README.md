# CRAZYAIGC Blog

CRAZYAIGC 官方博客文章仓库，用于存储新闻动态、AI 企业培训软文等内容。

## 目录结构

```
├── news/           # 新闻动态
├── training/       # AI 企业培训软文
└── insights/       # 行业洞察（可选）
```

## 文章格式

每篇文章需包含 frontmatter：

```yaml
---
title: "文章标题"
description: "文章描述（用于 SEO 和摘要）"
date: "2026-04-04"
category: "news" | "training" | "insights"
tags: ["标签1", "标签2"]
author: "CRAZYAIGC"
image: "/blog/cover.jpg"  # 可选
featured: true            # 可选，特色文章
---

# 正文内容

使用 Markdown 格式编写...
```

## 分类说明

| 分类 | 说明 |
|------|------|
| `news` | 公司新闻、产品更新、活动公告 |
| `training` | AI 培训相关软文、教程、案例 |
| `insights` | 行业洞察、趋势分析 |

## 更新流程

1. 在对应分类目录创建 `.md` 文件
2. 推送到 main 分支
3. 网站会自动获取最新内容（5 分钟缓存）

## SEO 建议

- **标题**：包含核心关键词，60 字以内
- **描述**：吸引点击，包含关键词，160 字以内
- **标签**：3-5 个相关标签
- **内容**：800-2000 字，包含小标题、列表、引用

## 许可证

Copyright © 2026 CRAZYAIGC. All rights reserved.
