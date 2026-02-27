---
title: 帖子模板
published: 2024-04-01
description: "如何使用这个博客模板。"
image: "./cover.jpeg"
tags: ["Fuwari", "博客", "自定义"]
category: 示例
draft: false
---

> Cover image source: [Source](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/208fc754-890d-4adb-9753-2c963332675d/width=2048/01651-1456859105-(colour_1.5),girl,_Blue,yellow,green,cyan,purple,red,pink,_best,8k,UHD,masterpiece,male%20focus,%201boy,gloves,%20ponytail,%20long%20hair,.jpeg)

This blog template is built with [Astro](https://astro.build/). For the things that are not mentioned in this guide, you may find the answers in the [Astro Docs](https://docs.astro.build/).

## 帖子示例

```yaml
---
title: My First Blog Post
published: 2023-09-09
description: This is the first post of my new Astro blog.
image: ./cover.jpg
tags: [Foo, Bar]
category: Front-end
draft: false
---
```
|名称         | 描述                                                                                                                                                                                                 |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `title`       | 帖子标题。                                                                                                                                                                                      |
| `published`   | 帖子发布的日期。                                                                                                                                                                           |
| `description` | 简要介绍一下帖子。显示在索引页。                                                                                                                                                   |
| `image`       | 帖子的封面图像路径。<br/>1. Start with `http://` or `https://`: Use web image<br/>2. Start with `/`: For image in `public` dir<br/>3. With none of the prefixes: Relative to the markdown file |
| `tags`        | 帖子标签。                                                                                                                                                                                       |
| `category`    | 帖子的分类。                                                                                                                                                                                   |
| `draft`        | 如果这篇帖子还是草稿，那就不会显示出来。                                                                                                                                                    |

## Post 文件的放置位置



你的帖子文件应该放在目录 `src/content/posts/` 里。你还可以创建子目录，更好地组织帖子和资源。

```
src/content/posts/
├── post-1.md
└── post-2/
    ├── cover.png
    └── index.md
```
