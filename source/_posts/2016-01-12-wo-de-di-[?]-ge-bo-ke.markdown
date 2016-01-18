---
layout: post
title: "我的第一个博客"
date: 2016-01-12 17:55:56 +0800
comments: true
categories: 
---


记录自己的博客之路

2016年1月12日 5:58:20

#前言

自己尝试搭建博客有两三天了，因为公司的事情，慢了一些，也走了很多弯路，记录下来，也算一个好的开篇。

#一些弯路

之前在《今日头条》上看了一篇几分钟就搭建好一个博客的，折腾了好久，也联系了作者，发现很多问题。他的是基于 Jekyll的Github Pages搭建的，声称只要几步，就可以搭建好，可是搭建好后：

一：fork后，改了名字，我clone下来，本地修改，push之后，博客内容很多时候没有变化

二：在github上内容都改变了，可是网页显示就是不变，有人说需要等一会，可是等了，也不行

#转机

忽然想到看过唐巧大神的博客迁移之类的文章，google之后，用了半天时间搭建起来，是基于Octopress的Github Pages。目前还是比较生疏，但是也是有所收获。

以下是唐巧的博客链接：

http://blog.devtang.com/blog/2012/02/10/setup-blog-based-on-github/

如果你的访问量很大可以参考：

http://blog.devtang.com/blog/2014/06/02/use-gitcafe-to-host-blog/

他的还有一些问题，因为时间稍微有些久远，软件版本问题之类的问题，相信大家能够解决，还有一些语法问题，可以参考官网：

http://octopress.org/

http://octopress.org/docs/deploying/github/

如果英文不好，可以谷歌，如果不会翻墙，这里提供一个免费的软件

https://github.com/getlantern/lantern

https://getlantern.org/

还有其他一些网址，会用到：

http://bbs.feng.com/read-htm-tid-6663858.html

请follow me https://github.com/Sky0372Lsk

#常用命令

rake new_post["article name"] 生成博文框架，然后修改生成的文件即可

rake generate 生成静态文件

rake deploy 发布文件

rake watch 检测文件变化，实时生成新内容

rake preview 在本机 4000 端口生成访问内容

感受一下强大的英文解释：

rake generate   # Generates posts and pages into the public directory

rake watch        # Watches source/ and sass/ for changes and regenerates

rake preview     # Watches, and mounts a webserver at http://localhost:4000

#可能会有很多问题，这几个参考一下
1.如果开始新建修改文章出现问题，这样解决：
$ ram gems use global
$ gem install bundler(sudo gem install bundler)

2.这个问题困扰好久，
参考goole：
大概意思是我的最新版本ruby不支持，运行如下命令：
rvm install ruby-2.2.0
gem install bundler
bundle install
rake generate

$ rake generate
## Generating Site with Jekyll
Configuration file: /Users/lishangkai/octopress/_config.yml
/Users/lishangkai/.rvm/gems/ruby-2.2.1/gems/posix-spawn-0.3.11/lib/posix_spawn_ext.bundle: [BUG] Segmentation fault at 0x00000000000418
ruby 2.2.1p85 (2015-02-26 revision 49769) [x86_64-darwin15]
-- Crash Report log information --------------------------------------------
See Crash Report log file under the one of following:
* ~/Library/Logs/CrashReporter
* /Library/Logs/CrashReporter
* ~/Library/Logs/DiagnosticReports
* /Library/Logs/DiagnosticReports
for more details.

-- Control frame information 
.........
.........
You may have encountered a bug in the Ruby interpreter or extension libraries.
Bug reports are welcome.
Don't forget to include the above Crash Report log file.
For details: http://www.ruby-lang.org/bugreport.html




#小总结

这里想说两点：

1.最近才感受到Google的强大，程序员早日远离百度。

2.多看英文文档，那里有最纯粹的技术。

我是李尚锴，感谢这段经历，让我成为了现在的我。

## 有问题请联系


# 联系方式

*   Email：17081440372@163.com
*   QQ/微信号：2539829389/李尚锴
*   Facebook：Shangkai Li
*   Twitter: ShangkaiLi
*   新浪微博: 青春最战役

* * *

# 个人信息

*   李尚锴/男/1992
*   本科/平顶山大学 
*   技术博客: <http://sky0372lsk.github.io>
*   Github: <https://github.com/Sky0372Lsk>
*   目前就职于：神汽在线

* * *



