# hexo-theme-simple99

## 介绍
基于hexo系统的一款简洁风博客主题，仓库将会长期维护，欢迎在 Issues 留言遇到的问题，或者来我的博客进行交流。

支持pc端、移动端完美显示。[English document](https://github.com/shuxhan/hexo-theme-simple99/blob/main/README.md)

欢迎使用本主题的在在Issues留下你的站点。

## 主题使用展示
[树寒的博客](https://shuxhan.com)(作者)

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
- [x] 置顶

## 安装教程

### 选择一

1. 下载主题源码
```shell
cd themes
git clone https://github.com/shuxhan/hexo-theme-simple99.git
```
2. _config.yml 
```js
theme: hexo-theme-simple99
```
3. 运行项目
```shell
hexo s
```
4. 发布文章

这边强烈建议使用以下命令发布新的内容到github仓库中
```shell
hexo clean && hexo g -d
```

### 选择二

直接点击code下载原文件，然后拷贝到您的`themes`文件夹内

然后修改项目配置中的`theme: hexo-theme-simple99`

## 安装插件依赖

每个hexo主题除了默认的依赖，还有各个作者后期引入的功能插件，每个主题不尽相同，本主题建议安装
```shell
npm install --save hexo-generator-search
```

## 使用说明

1.  可依靠[_config.yml]主题配置对博客进行配置
2.  评论系统集成了 valine 和 twikoo 两种，可以参照官方文档进行配置，`../themes/hexo-theme-simple99/layout/partials/comments.ejs`文件是评论系统的配置文件
3. ［关于］
   修改时进入`../themes/hexo-theme-simple99/layout/about.ejs`填写自己的内容，如不需要[关于]，请在主题配置中注释掉`about: /about`
3.  文章生成(所有标签内容，使用时可酌情选取自己所需)
```
---
title: hello,world
date: 2020-12-17  # 发布时间
updated: 2020-12-26  # 最后更新时间
tags: 标签
categories: 分类
top: 9   # 文章是否置顶，默认不写top，不置顶；如果置顶可选择数字，如果有多个置顶，根据数字大小进行排序
toc: true # 是否生成目录(true生成；默认不写toc则不生成)
cover:  # 标题背景图片
---
```
4. 如有其他问题，
- [x] 可在 Issues 留言，
- [x] 给 zsh981109@163.com 发一封电子邮件，
- [x] 在我的博客留言区进行[留言](https://shuxhan.com/message)，
   我都会在第一时间看到并回复

## 参与贡献

1.  `Fork` 或者 `Star` 本仓库，为作者增加一点鼓励
2.  在 Issues 提问或讨论


## 作者

[shuxhan](https://github.com/shuxhan)


