# hexo-theme-simple99

![](https://cdn.jsdelivr.net/gh/Nov8nana/pic-cdn@685e042725027993ee8f76f0cc691a5dc82066b1/2021/05/24/6b6e33b20219b7d305acc92034e4f10d.png)

## 介绍

[English](https://github.com/Nov8nana/hexo-theme-simple99/blob/main/README.md) | 中文简体

基于hexo系统的一款简洁风博客主题，主题色调偏淡色，视觉效果柔和，采用双栏卡片式设计，功能齐全。

如果你能在使用前点一个小小的 star ，作者将万分感谢；当然如果你觉得麻烦，也没有关系，欢迎使用主题，希望能给您带来不错的体验。

仓库将会长期维护，欢迎在 Issues 留言遇到的问题，或者来我的博客进行交流。如果你想使用某些功能，而主题不具备，欢迎在 Issues 提出你的想法，作者觉得不错的建议都将会采纳。

支持pc端、移动端显示。

欢迎使用本主题的博客在 Issues 留下你的站点。

ps：本主题耦合性极低，可自由搭配页面的组合，感兴趣的同学可以在代码里面尽情摸索。

**提示：如果报错，请检查是否安装插件依赖！**

## 下载地址

* github 仓库：[https://github.com/Nov8nana/hexo-theme-simple99](https://github.com/shuxhan/hexo-theme-simple99)
* gitee 仓库：[https://gitee.com/shuxhan/hexo-theme-simple99](https://gitee.com/shuxhan/hexo-theme-simple99)

## 主题使用展示

[主题演示](https://simple.cn)

## 主题页面

- 首页
- 归档
- 分类
- 标签
- 留言
- 关于

## 功能

集成了一个博客应该具备的功能，可在使用中探索，包括但不限于：评论，目录，置顶，访客统计，分类标签等。

你会发现很多不一样的东西，某些内容我没有放在配置中，但是不影响你的正常使用，而是作为惊喜等着你去发现。

## 安装教程

### 选择一

1. 下载主题源码
```shell
cd themes
git clone https://github.com/Nov8nana/hexo-theme-simple99.git
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

每个hexo主题除了默认的依赖，还有各个作者后期引入的功能插件，每个主题不尽相同。

下面是本主题建议安装的插件，可根据自己的需求进行下载：

1. 搜索功能插件
```shell
npm install --save hexo-generator-search
```

2. 博客总字数统计
```shell
npm install --save hexo-wordcount
```

3. 置顶功能插件
```shell
npm uninstall hexo-generator-index --save
npm install hexo-generator-index-pin-top --save
```

4. 实时编辑预览插件

这是一个辅助插件，使用者可自由选择是否安装。

每当你 `ctrl + s` 保存代码时，浏览器会自动刷新，而不是手动 `f5` ，并且终端和浏览器会弹出一个短暂的字幕提醒页面已修改。

```shell
npm install --save hexo-browsersync
```

## 使用说明

1.  可依靠 `config.yml` 主题配置对博客进行配置
2.  评论系统内置 twikoo 静态评论系统，可以参照 [官方文档](https://twikoo.js.org)进行配置，`../themes/hexo-theme-simple99/layout/partials/comments.ejs`文件是评论系统的配置文件
3. ［关于］
   修改时进入`../themes/hexo-theme-simple99/layout/about.ejs`填写自己的内容，如不需要[关于]，请在主题配置中注释掉`about: /about`
3.  文章生成(所有标签内容，使用时可酌情选取自己所需)
```
---
title: hello,world
date: 2020-12-17  # 发布时间
tags: 标签
categories: 分类
top: 9   # 文章是否置顶，默认不写top，不置顶；如果置顶可选择数字，如果有多个置顶，根据数字大小进行排序
toc: true # 是否生成目录(true生成；默认不写toc则不生成)
cover:  # 标题背景图片
---
```
4. 如有其他问题，
- [x] 可在 Issues 留言，
- [x] 给 shuxhan@163.com 发一封电子邮件，
- [x] 在我的博客进行 [留言](https://imzsh.com/about)，
   
我都会在第一时间看到并回复。

## 常见问题

[点击查看常见问题](https://github.com/Nov8nana/hexo-theme-simple99/issues?q=is%3Aissue+is%3Aopen+label%3A%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)

## 参与贡献

1.  `Star` 或者 `Fork` 本仓库，为作者增加一点鼓励
2.  在 Issues 提问或讨论

## 作者

[Nov8nana](https://github.com/Nov8nana)
