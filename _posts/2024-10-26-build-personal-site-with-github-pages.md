---
layout: post
title: 利用github pages构建个人网站
---

本文介绍如何使用GitHub创建个人的网站或博客。在此之前，请确保你已经拥有一个github账号，否则请访问<a href="https://github.com/" target="_blank">GitHub</a>注册一个账号。

**Tips**
注册账号时请为你填写一个**好看**的用户名，因为它将是你在GitHub上使用众多功能时的链接凭证。请尽量不要胡乱输入一个用户名。

## 1.创建仓库

GitHub有个人站点[user]和项目站点[project]的之分。

GitHub个人站点将为你提供免费域名以供访问。域名格式为：https://[username].github.io。其中username就是你的用户名，域名格式在Github上是固定的，它将是你的个人主页地址。如果你自己购买了域名，也可以用自己购买的域名与这个地址映射。

接下来我们来创建仓库，这里建议尽量创建公共仓库(Public)，因为私有仓库(Private)在 GitHub Action有免费额度限制。

登录GitHub后，点击右上角的"+"号按钮创建一个新的仓库"New repository"。

若将仓库名"Repository Name"命名为：[username].github.io，确认创建后你的**个人站点**就创建成功了。访问地址：https://[username].github.io

若仓库名命名不是`[username].github.io`的格式，比如你命名成"HelloGit"，则在GitHub上创建一个名为"HelloGit"的项目仓库，同时它也将是你的**项目站点**。访问地址：https://[username].github.io/[repositoryname]

观察上面的2个访问地址，可以发现项目站点的访问地址只是在个人站点链接后增加"/仓库名"拼接的。

那么接下来都将以个人站点的仓库作为后续内容的讲述标本。

我们可以在仓库新建一个文件命名为：index.html，这是主页文件。文件内容可以随便填写，比如"Hello world!"，然后点击提交。此时我们在浏览器访问个人站点或项目站点就可以看到这个页面上的内容了。站点地址默认会读index.html/index.md/README.md等文件的内容。


## 2.启用Github pages

- 点击仓库的Settings菜单进入配置页。
- 选择左侧栏中**Code and automation**下的Pages进入GitHub Pages设置页。
- 在**Build And Deplovment**中点击**Source**下拉框，选择"Deploy from a branch"，Branch 选择 main。
- 点击Save保存。
  
<img src="/notes/assets/pictures/GitHub-Settings-1.png" />

>启用Github Pages会创建仓库的部署。在等待部署期间，GitHub Actions可能需要长达一分钟的时间才能响应，需要耐心等待。
>tips：在Pages设置的顶部，会出现你的网站链接，复制链接或者点击"Visit Site"按钮可以访问你的GitHub Pages站点。

如果你使用的是项目仓库，Setting菜单下的


## 2.定制主题

## 3.编写博客文章
