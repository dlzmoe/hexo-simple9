# hexo-theme-simple99

## Introduction

A simple style blog theme based on the hexo system, the theme is pale in color, and the visual effect is soft. It adopts a double-column card design and is fully functional.

If you can click a small star before using it, the author would be very grateful; of course, if you find it troublesome, it doesn't matter, welcome to use the theme, and hope to bring you a good experience.

If you think the download speed is too slow, please click [here](https://gitee.com/shuxhan/hexo-theme-simple99), the author will update the warehouse synchronously in gitee.

The warehouse will be maintained for a long time. Welcome to leave a message on Issues or come to my blog to communicate.If you want to use certain functions, but the theme does not have it, you are welcome to submit your ideas in Issues, and the author thinks good suggestions will be adopted.

Supports perfect display on PC and mobile terminals.[查看中文文档](https://github.com/shuxhan/hexo-theme-simple99/blob/main/README-zh.md)

Welcome to use the blog of this topic and leave your site in Issues.

ps：The coupling of this theme is extremely low, and the combination of pages can be freely matched, and interested students can explore in the code.

## Theme demo

[shuxhan's blog](https://simple99.cn)(author)

## Page

- home
- archive
- categories
- tags
- message
- about

## Features

It integrates the functions that a blog should have, and can be explored in use, including but not limited to: comments, directories, topping, visitor statistics, classification tags, etc.

You will find a lot of different things, some content I did not put in the configuration, but it does not affect your normal use, but as a surprise waiting for you to discover.

## Installation tutorial

### Choose one

1. Download theme source code

```shell
cd themes
git clone https://github.com/shuxhan/hexo-theme-simple99.git
```

2. _config.yml 

```js
theme: hexo-theme-simple99
```

3. Run the project

```shell
hexo s
```

4. post article

It is strongly recommended to use the following command to publish new content to the github repository

```shell
hexo clean && hexo g -d
```

### Choose two

Click the code directly to download the original file, and then copy it to your `themes` folder.

Then modify the `theme: hexo-theme-simple99` in the project configuration

## Install plugin dependencies

In addition to the default dependencies, each hexo theme also has functional plug-ins introduced later by each author. Each theme is different.

The following are the plug-ins recommended for this theme, which can be downloaded according to your needs:

1. Search function plugin
```shell
npm install --save hexo-generator-search
```

2. Total word count of blog
```shell
npm i --save hexo-wordcount
```

3. Top function plugin
```shell
npm uninstall hexo-generator-index --save
npm install hexo-generator-index-pin-top --save
```

4. Real-time edit preview plugin

This is an auxiliary plug-in, users can freely choose whether to install it.

Whenever you save the code with `ctrl + s`, the browser will automatically refresh instead of manual `f5`, and the terminal and browser will pop up a short subtitle to remind the page has been modified.

```shell
npm install --save hexo-browsersync
```

## Instructions for use

1.  The blog can be configured with the [_config.yml] theme configuration
2.  The comment system has built-in twikoo static comment system, you can refer to [official document](https://twikoo.js.org) for configuration, `../themes/hexo-theme-simple99/layout/partials/comments.ejs` file is Comment system configuration file
3.  ［about］
    When modifying, enter `../themes/hexo-theme-simple99/layout/about.ejs` to fill in your own content, if you don’t need [About], please comment out `about: /about` in the theme configuration
4.  Article generation (all label content, you can choose what you need when using it)

```md
---
title: hello,world
date: 2020-12-17  # release time
tags: tags
categories: categories
top: 9   # Whether the article is topped or not, the default is not to write top, not top; if the top is selected, the number can be selected, if there are multiple tops, sort by number
toc: true # Whether to generate a directory (true generation; default does not write toc, no generation)
cover:  # Title background image
---
```

4. If you have other questions

- [x] You can leave a message in Issues
- [x] Send an email to zsh981109@163.com
- [x] [Message](https://shuxhan.com/message) in the message area of my blog,

I will see and reply the first time

## Common lofty mention

[Click to view FAQ](https://github.com/shuxhan/hexo-theme-simple99/issues?q=is%3Aissue+is%3Aopen+label%3A%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)

## Participate in contribution

1.  `Star` or `Fork` this repository, add a little encouragement to the author
2.  Ask or discuss in Issues

## Author

[shuxhan](https://github.com/shuxhan)
