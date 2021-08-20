---
title: Hello World
abbrlink: 16107
---

## 为什么搭建博客

最初搭建博客是在一年前了，有点跟风的样子，看到朋友都搭建了一下，作为一个程序员，也是应该有自己的博客嘛2333。

然而当时没有什么要分享的内容，主要目的是用来存放一下笔记，然后写在简历中用来找工作（然后主程告诉我博客对这方面并没有太大用处，遂失去兴趣）。

之后在与 ioa 的交流中，才知道博客作为一个他人了解自己的窗口，分享自己的想法，让对自己感兴趣的人能够更加了解自己，这也是我一直希望的，虽然作为一个 baka 但还是希望能够有人理解我是一个思想比较丰富的 baka（bushi）。

## 博客放些什么好呢

先从比较轻松的开始吧，个人兴趣的总结，日常对动画影视书籍的观后感。
以及对经历的事情，阶段性的总结

由于自己的笔记非常结构化（其实就是只有结构，注重实用性和快捷编写，很难读x），之后，估计，可能，会考虑放上来，ummm？

## 博客搭建路程

20 年 3 月左右，在 github 上搭建的博客因为只有博客生成的静态页面，没有上传 hexo 博客项目本体（留在电脑上）。

再之后，20 年 7 月左右，玖给我搭建了基于 typecho 的博客，服务器就置于樱游社，重要的是樱游社的那个域名很喜欢，就选用了它（其实就是改一下 CNAME 就能搞定的事情）。那个时候用 typecho 博客可以直接在网页内编辑，一些简单的事情不用再直接去操控服务端，但是之后发现要连接服务器还是比较麻烦，就也没有继续搞了。

然后，社团的阿里云服务器到期了，数据清空了，完全找不到，也没有多余的服务器（因为要求一个服务器只做一件事情），然后只要了社团 CNAME 作为域名转接，继续使用 Github Page。

更换电脑的时候，看到 blog 的项目文件夹，想着自己也不怎么会用到博客了，也就没有备份一份x。也就是，只能重新搭建了。
不过好在最后重新搭建还是比较快速的（并不顺畅！），也是重新熟悉一下 Hexo 的一些配置。

中途一直卡在了错误 `TypeError: Cannot read property 'enable' of undefined at Hexo.logic`
原因是配置中缺少选项，但怎么都找不到

最后直接将炎忍的博客项目配置全部复制过来，只修改内容，少量删除一些东西，最后 generate 完成。

## 配置路程

### 图床

服务器放在 GitHub 上，加载速度慢最受影响的其实主要是图片。

本来想优先选择能够允许 NSFW 图片的图床，但是又想到，我也不会没事在自己笔记里放涩图，更不会在博客公开发这些东西xxx，这是一个比较特别的但又还没遇到的需求（遇到了就使用一个特别的图床吧），最后随着 Typora 的图片上传选项，使用了 picGo 中默认的 sm.ms 图床。

### 文件链接

因为有时候只想专注于自己的笔记文件夹，不想两个文件切来切去的，有时候还要同步。最后用了 Xyplorer 的复制为硬链接功能，应该系统内置的也能做到（没找过教程），这样两边的更改都是完全串联起来的，不是简单的快捷方式。

### steam

https://www.steamsignature.com/

### 音乐播放器 APlayer

https://butterfly.js.org/posts/507c070f/#%E6%8F%92%E5%85%A5Aplayer-html

## 待配置

- 分类、Tag、友链
- Live2d Neptune 模型
- 主题配色（可能就直接找哪个地方抄一份）

> 下面是自带 HelloWorld

Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Built-In Hello World

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
