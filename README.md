# hexo-theme-anghunk-main

## 介绍
基于hexo系统的一款简洁风博客主题

[demo](https://shuxhan.com)

## 主题页面
- 首页
- 归档
- 分类
- 标签
- 留言
- 关于

## 安装教程

1. 下载主题源码
```shell
cd themes
git clone https://github.com/anghunk/hexo-theme-anghunk-main.git
```
2. _config.yml 
```js
theme: anghunk
```
3. 运行项目
```shell
hexo s
```

## 使用说明

1.  可依靠[_config.yml]主题配置对博客进行配置
2.  评论系统集成了 valine 和 twikoo 两种，可以参照官方文档进行配置，`../themes/anghunk/layout/partials/comments.ejs`文件是评论系统的配置文件
3.  文章生成
```
---
title: hello,world
date: 2020-12-17
tags: 标签
categories: 分类
toc: true # 是否生成目录(true生成；默认不写toc则不生成)
cover:  # 标题背景图片
---
```
4. 如有其他问题，可在 Issues 留言，
   或者给 zsh981109@163.com 发一封电子邮件，
   或者在我的博客留言区进行[留言](https://shuxhan.com/messgae)，
   我都会在第一时间看到并回复

## 参与贡献

1.  Fork 本仓库
2.  在 Issues 提问或讨论


## 作者

[anghunk](https://github.com/anghunk)


