# Thcrap CN Mirror special version
## What is this？

We found the user in China download the patch at a intolerable speed.So we decided to establish a mirror site to solve this problem.

Now we make a site already,but thcrap always tries to access the official mirror source when downloading patches.That means the whole project we did actually for nothing but waste our time.

At this moment,brliron,one of the developer maintaining the thcrap, helped us to solve this trouble.He add a function that allows people compile the thcrap to specify a source server address.So it becomes be possible that we make a special version of thcrap that access the 3rd mirror site only, instead of the original one.

## How does it work?

We make a GitHub Action script to compile thcrap with our mirror url automantically.Then we release the files we build and supply a high speed download link on our site so that everyone could obtain them conveniently.

## OK,I already known.So where could I get it?

You could have it in this repository, if you find its difficult to access GitHub,please obtain the files by these links:

# Thcrap中文镜像站特别版本

## 简介

由于thcrap的源服务器在国外，因此在国内下载补丁十分缓慢。为了解决这个问题，我们就搭了一个中文镜像站。

现在镜像站已经搭建好了，thcrap支持命令行方式指定源服务器，从而允许其他人搭建自己的源服务器。但是thcrap将官方源地址硬编码到了配置器内，因此在未指定镜像源地址时仍会访问官方的服务器，从而导致我们的镜像站并无实际作用。

我们将这个问题反馈给了thpatch团队，brliron（维护thcrap主要开发者之一）就为其添加了一项功能——允许编译时指定源服务器地址。这样一来我们就可以制作出完全脱离官方服务器只访问中文镜像站的thcrap版本。

## 工作原理

利用GitHub Action自动拉取最新版thcrap源码进行编译，指定我们的镜像站作为源服务器。之后我们将编译好的程序发布到该仓库下。

## 下载链接

可以在本仓库或者镜像站进行下载，链接如下：


（由于本人正在备考，因此本项目进展会比较缓慢，待完成后另行通知。）