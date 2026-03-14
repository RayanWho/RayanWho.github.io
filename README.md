# RayanWho的个人博客

这是使用GitHub Pages和Jekyll搭建的个人博客。

## 本地开发

1. 确保安装Ruby和Bundler。
2. 克隆仓库：`git clone https://github.com/RayanWho/RayanWho.github.io.git`
3. 安装依赖：`bundle install`
4. 运行本地服务器：`bundle exec jekyll serve`
5. 访问 http://localhost:4000 查看博客。

## 部署到GitHub Pages

将更改推送到main分支，GitHub Pages会自动构建和部署站点。

## 添加新文章

在`_posts`目录中创建新文件，格式为`YYYY-MM-DD-title.md`，包含front matter。

例如：

```
---
layout: post
title: "我的第一篇文章"
---

文章内容...
```
