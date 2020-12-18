# hexo-theme-anghunk-main

## 介绍
基于hexo系统的一款简洁风博客主题，仓库将会长期维护，欢迎在 Issues 留言遇到的问题，或者来我的博客进行交流

## 主题使用展示
[张舒涵的博客](https://shuxhan.com)(作者)

## 主题页面
- 首页
- 归档
- 分类
- 标签
- 留言
- 关于

## 已有功能
- [x] 目录
- [x] 评论
- [ ] 说说

## 安装教程

### 选择一

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

### 选择二

直接点击code下载原文件，然后拷贝到您的`themes`文件夹内

然后修改项目配置中的`theme: anghunk`

## 使用说明

1.  可依靠[_config.yml]主题配置对博客进行配置
2.  评论系统集成了 valine 和 twikoo 两种，可以参照官方文档进行配置，`../themes/anghunk/layout/partials/comments.ejs`文件是评论系统的配置文件
3. ［关于］
   修改时进入`../themes/anghunk/layout/about.ejs`填写自己的内容，如不需要[关于]，请在主题配置中注释掉`about: /about`
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
4. 如有其他问题，
- [x] 可在 Issues 留言，
- [x] 给 zsh981109@163.com 发一封电子邮件，
- [x] 在我的博客留言区进行[留言](https://shuxhan.com/messgae)，
   我都会在第一时间看到并回复

## 参与贡献

1.  `Fork` 或者 `Star` 本仓库，为作者增加一点鼓励
2.  在 Issues 提问或讨论


## 作者

[anghunk](https://github.com/anghunk)


