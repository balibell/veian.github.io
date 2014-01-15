---
layout: post
title:  "配置ubuntu开发环境"
description: "配置ubuntu开发环境"
categories: tools
tags: [frontend]
---

## 使用到的命令

### 查看系统信息（32位 or 64位）

``` sh
$ uname -a
```

``` sh
$ uname -m
$ arch
$ file /bin/cat
```

查看cpu信息

``` sh
$ more /proc/cpuinfo
```

查看 LINUX是32位还是64位

``` sh
$ su - root
# file /sbin/init
```

### tar 打包，解包

`-f` 指定包的文件名


`-c` 创建包

`-r` 追加

`-u` 更新文件

`-t` 列出文件

`-x` 解包

`-v` 查看


`-z` 调用`gzip`
<<<<<<< HEAD:_drafts/config-ubuntu-dev.md
`-j` 调用`bzip2`
=======

`-j` 调用`gzip`

>>>>>>> 36188af5cf7fcf0a981f06028cbd6182802f2aab:_posts/2014-01-13-config-ubuntu-dev.md
`-Z` 调用`compress`

## 安装 Sublime Text 2

``` sh
$ sudo add-apt-repository ppa:webupd8team/sublime-text-2
$ sudo apt-get update
$ sudo apt-get install sublime-text
# or dev version
# sudo apt-get install sublime-text-dev
```

更多：[http://www.webupd8.org/2011/03/sublime-text-2-ubuntu-ppa.html](http://www.webupd8.org/2011/03/sublime-text-2-ubuntu-ppa.html)

Sublime Text 2 不能输入中文