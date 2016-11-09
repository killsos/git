# Git远程操作详解 学习笔记

![git 原理](git.jpg)

### 一、git clone

***
> 远程操作的第一步，通常是从远程主机克隆一个版本库，这时就要用到git clone命令。

    git clone <版本库的网址>

> 比如，克隆jQuery的版本库。

    git clone https://github.com/jquery/jquery.git

> 该命令会在本地主机生成一个目录，与远程主机的版本库同名。如果要指定不同的目录名，可以将目录名作为git clone命令的第二个参数
