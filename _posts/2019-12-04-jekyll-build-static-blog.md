---
layout: post
title:  "jekyll 搭建静态博客"
date:   2019-12-04 20:26:50 +0800
categories: tool jekyll
tags: jekyll github-page
---









jekyll + github page 搭建静态博客

安装 --> 创建博客 --> 配置 --> 本地运行 --> 部署









### 安装

<https://rubyinstaller.org/downloads/>

- [Ruby+Devkit 2.6.5-1 (x64)](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.6.5-1/rubyinstaller-devkit-2.6.5-1-x64.exe)



<https://rubygems.org/pages/download>

* ZIP



cd 到解压目录

- ruby setup.rb



安装Jekyll

- gem -v
- gem install jekyll



### 创建博客

创建博客

- 新建工作区

  - md myBlog
- cd 到工作区

  - cd myBlog
- 执行 `jekyll new name(创建新的工作区)`

  - jekyll new myblog

- cd 到博客文件夹，开启服务器

  - jekyll serve --watch

    > watch为了检测文件夹内的变化，即修改后不需要重新启动jekyll

### 配置



### 本地运行



### 部署