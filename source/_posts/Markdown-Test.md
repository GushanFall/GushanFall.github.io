---
title: Markdown Test
tags:
  - test
categories:
  - 测试
toc: true
date: 2025-03-25 23:53:59
mathjax: true
---
# 1 Latex 公式编辑
在写文章的时候，免不了输入公式，所以首先测试能否使用 `$...$` 的形式来输入 Latex 公式。但是发现并没有成功渲染。

经过一番搜索，终于通过 `hexo-renderer-pandoc` 和 `hexo-filter-mathjax` 成果解决问题。

行内公式：$x=\alpha$

行间公式：$$x=\beta$$

# 2 