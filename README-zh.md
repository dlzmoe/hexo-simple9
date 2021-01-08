# hexo-theme-simple99

## 介绍

基于hexo系统的一款简洁风博客主题，主题色调偏淡色，视觉效果柔和，采用双栏卡片式设计，功能齐全。

仓库将会长期维护，欢迎在 Issues 留言遇到的问题，或者来我的博客进行交流。

支持pc端、移动端完美显示。[English document](https://github.com/shuxhan/hexo-theme-simple99/blob/main/README.md)

欢迎使用本主题的博客在 Issues 留下你的站点。

ps：本主题耦合性极低，可自由搭配页面的组合，感兴趣的同学可以在代码里面尽情摸索。

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

每个hexo主题除了默认的依赖，还有各个作者后期引入的功能插件，每个主题不尽相同。

下面是本主题建议安装的插件，可根据自己的需求进行下载：

1. 搜索功能插件
```shell
npm install --save hexo-generator-search
```

2. 置顶功能插件
```shell
npm uninstall hexo-generator-index --save
npm install hexo-generator-index-pin-top --save
```

3. 实时编辑预览插件

这是一个辅助插件，使用者可自由选择是否安装。

每当你 `ctrl + s` 保存代码时，浏览器会自动刷新，而不是手动 `f5` ，并且终端和浏览器会弹出一个短暂的字幕提醒页面已修改。

```shell
npm install --save hexo-browsersync
```

## 使用说明

1.  可依靠[_config.yml]主题配置对博客进行配置
2.  评论系统内置 twikoo 静态评论系统，可以参照[官方文档](https://twikoo.js.org)进行配置，`../themes/hexo-theme-simple99/layout/partials/comments.ejs`文件是评论系统的配置文件
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
- [x] 给 zsh981109@163.com 发一封电子邮件，
- [x] 在我的博客留言区进行[留言](https://shuxhan.com/message)，
   
我都会在第一时间看到并回复。

## 参与贡献

1.  `Star` 或者 `Fork` 本仓库，为作者增加一点鼓励
2.  在 Issues 提问或讨论

## 作者

[shuxhan](https://github.com/shuxhan)

## 更新日志

### 2021.01.08

1. 对 aside 部分格式重新整合，并增加个人简介。
2. 新增访客人数统计。
3. 新增新年挂件。

### 2021.01.06

1. 将主色系从淡蓝色转为灰黑色。（可以自由调整色彩，目标文件 `main.css`）
2. 将首页目录调整为卡片式。
3. 调整布局细节。

### 2020.12.xx

1. 增加评论功能，采用 twikoo 静态评论系统。
2. 目录功能，页面滚动时保持在右侧 aside 。
3. 适配移动端。