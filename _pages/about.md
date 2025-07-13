---
permalink: /
title: "Academic Pages 是一个适合学术个人网站的 GitHub Pages 模板，开箱即用"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

这是一个基于 [Academic Pages 模板](https://github.com/academicpages/academicpages.github.io) 并托管在 GitHub Pages 上的个人主页。[GitHub Pages](https://pages.github.com) 是一项免费服务，可以根据你在 GitHub 仓库中的代码和数据自动生成和托管网站，每次提交都会自动更新。本模板基于 [Minimal Mistakes Jekyll 主题](https://mmistakes.github.io/minimal-mistakes/)（作者 Michael Rose）进行扩展，专为学者设计，支持发表成果、演讲、教学、作品集、博客文章和自动生成的简历等内容。当然，这些功能也非常适合需要展示专业形象的任何人！

你可以现在就 fork [本模板](https://github.com/academicpages/academicpages.github.io)，修改配置和 Markdown 文件，添加自己的 PDF 和其他内容，免费拥有属于你自己的网站，无广告！

数据驱动的个人网站
======
与许多基于 Jekyll 的 GitHub Pages 模板类似，Academic Pages 实现了内容与展示分离。你的网站内容和元数据以结构化 Markdown 文件存储，主题文件则定义如何将这些内容和元数据渲染为 HTML 页面。你只需将这些 Markdown（.md）、YAML（.yml）、HTML 和 CSS 文件保存在公开的 GitHub 仓库中。每次提交和推送更新后，[GitHub Pages](https://pages.github.com/) 服务会自动生成静态 HTML 页面并免费托管。

许多动态内容管理系统（如 Wordpress）的功能都可以通过这种方式实现，资源消耗更少，安全性更高。你可以随意修改主题而不影响内容。如果你在 Jekyll/HTML/CSS 上出现了无法修复的问题，你的 Markdown 文件（如演讲、发表等）依然安全，可以回滚或重建仓库——只要保存好 Markdown 文件即可。你还可以编写脚本处理站点上的结构化数据，比如 [这个例子](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) 会分析演讲元数据并生成[演讲地图](https://academicpages.github.io/talkmap.html)。

模板还支持以下常用工具：
- [MathJax](https://www.mathjax.org/) 数学公式
- [Mermaid](https://mermaid.js.org/) 流程图/图表
- [Plotly](https://plotly.com/javascript/) 绘图

快速开始
======
1. 注册 GitHub 账号并验证邮箱（必需）
1. 点击右上角 "Use this template" 按钮 fork [本模板](https://github.com/academicpages/academicpages.github.io)
1. 进入仓库设置，将仓库重命名为 "[你的 GitHub 用户名].github.io"，这也将成为你网站的访问地址
1. 配置站点信息并创建内容（见下文，也可参考[这个示例差异](http://archive.is/3TPas)和[示例网站](https://getorg-testacct.github.io)）
1. 上传文件（如 PDF、zip 等）到 files/ 目录，访问地址为 https://[你的 GitHub 用户名].github.io/files/example.pdf
1. 在仓库设置的 "GitHub Pages" 部分查看网站状态

全站配置
------
主配置文件为根目录下的 [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml)，用于定义侧边栏和全站功能。请将默认变量替换为你自己的信息。顶部菜单配置在 [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml)。例如，如果你不需要作品集或博客，可以在 navigation.yml 中移除对应项。

内容与元数据
------
每类内容对应一个 Markdown 文件，分别存放在 _publications、_talks、_posts、_teaching、_pages 等目录。例如，每个演讲是 _talks 目录下的一个 Markdown 文件，顶部为 YAML 结构化数据，主题会自动解析并生成页面。相同的数据会用于 [演讲页面](https://academicpages.github.io/talks)、[个人简历](https://academicpages.github.io/cv)、[演讲地图](https://academicpages.github.io/talkmap.html) 等（可运行 [python 文件](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) 或 [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) 生成地图 HTML）。

**Markdown 生成器**

本仓库包含 [一组 Jupyter notebook](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
)，可将包含演讲/报告结构化数据的 CSV 转换为 Academic Pages 模板所需的 Markdown 文件。示例 CSV 可参考我在 stuartgeiger.com 个人网站使用的文件。我的常规流程是维护一个发表和演讲的表格，然后用 notebook 生成 Markdown 文件，最后提交到仓库。

如何编辑你的 GitHub 仓库
------
许多人使用 git 客户端在本地创建文件后推送到 GitHub。如果你不熟悉 git，也可以直接在 github.com 网页端编辑配置和 Markdown 文件。进入文件页面（如 [这个例子](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md)），点击右上角铅笔图标即可编辑。点击垃圾桶图标可删除文件。你还可以在目录下点击 "Create new file" 或 "Upload files" 按钮新建或上传文件。

示例：编辑演讲 Markdown 文件
![编辑演讲 Markdown 文件](/images/editing-talk.png)

更多信息
------
更多配置说明见[官方指南](https://academicpages.github.io/markdown/)、[Wiki](https://github.com/academicpages/academicpages.github.io/wiki)，如有疑问可在 [GitHub Discussions](https://github.com/academicpages/academicpages.github.io/discussions) 提问。主题的[原始文档](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)也有帮助。
