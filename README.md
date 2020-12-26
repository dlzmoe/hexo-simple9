# hexo-theme-simple99

## Introduction

Introduce a simple blog theme based on the hexo system. The warehouse will be maintained for a long time. Welcome to leave a message on Issues or come to my blog to communicate.

Supports perfect display on PC and mobile terminals.[查看中文文档](https://github.com/shuxhan/hexo-theme-simple99/blob/main/README-zh.md)

Welcome to use this theme to leave your site on Issues.

## Theme use display

[shuxhan's blog](https://shuxhan.com)(author)

## Topic page

- home
- archive
- categories
- tags
- message
- about

## Existing function

- [x] table of Contents
- [x] leave a message
- [x] Make

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

In addition to the default dependencies of each hexo theme, there are functional plug-ins introduced later by each author. Each theme is different. This theme recommends installing

```shell
npm install --save hexo-generator-search
```

## Instructions for use

1.  The blog can be configured with the [_config.yml] theme configuration
2.  The comment system integrates valine and twikoo. You can refer to the official documentation for configuration. The file `../themes/hexo-theme-simple99/layout/partials/comments.ejs` is the configuration file of the comment system
3.  ［about］
    When modifying, enter `../themes/hexo-theme-simple99/layout/about.ejs` to fill in your own content, if you don’t need [About], please comment out `about: /about` in the theme configuration
4.  Article generation (all label content, you can choose what you need when using it)

```md
---
title: hello,world
date: 2020-12-17  # release time
updated: 2020-12-26  # Last update time
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

## Participate in contribution

1.  `Fork` or `Star` this repository, add a little encouragement to the author
2.  Ask or discuss in Issues


## Author

[shuxhan](https://github.com/shuxhan)
