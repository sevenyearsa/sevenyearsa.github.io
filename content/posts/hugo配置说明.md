---
date: '2024-11-22T20:14:58+08:00'
draft: false
title: 'Hugo配置说明'
author: 'sevenyearsa'
ShowWordCount: false
ShowReadingTime: false
---

## 引言
什么都没有

### 项目结构
```
your-hugo-site/
│
├── archetypes/            # 文章模板目录
│   └── default.md        # 默认的文章模板
│
├── assets/               # 需要处理的资源文件
│   ├── css/             # CSS 文件
│   └── js/              # JavaScript 文件
│
├── content/             # 网站内容目录
│   ├── posts/          # 博客文章
│   ├── about/          # 关于页面
│   └── projects/       # 项目页面
│
├── data/               # 配置数据文件目录
│   ├── authors.yaml    # 作者信息
│   └── menu.yaml       # 菜单配置
│
├── layouts/            # 布局模板目录
│   ├── _default/      # 默认模板
│   ├── partials/      # 部分模板
│   └── shortcodes/    # 短代码模板
│
├── public/            # 构建生成的静态文件（不要手动修改）
│
├── resources/         # 缓存文件目录（不要手动修改）
│
├── static/           # 静态文件目录
│   ├── images/      # 图片文件
│   ├── css/         # 静态 CSS 文件
│   └── js/          # 静态 JavaScript 文件
│
├── themes/          # 主题目录
│   └── PaperMod/    # PaperMod 主题
│
├── config.toml      # 网站配置文件（或 hugo.yaml）
└── hugo.toml        # Hugo 特定配置文件
```