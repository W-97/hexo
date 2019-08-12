---
title: first
date: 2019-08-02 15:17:02
tags: 
    - 1.
    - 2.
---
### 首先
安装Node.js以及Git
若安装上述程序 使用npm完成Hexo安装
npm install -g hexo-cli
## 创建Hexo项目
先创建本地项目文件夹
cd到改目录下
执行 hexo init   建立当前文件夹下网站
执行 npm install  下载到本地
继续执行 hexo new [layout]   新建一片文章
新建文章后，生成静态文件   hexo generate/ hexo g
[-d, --deploy]  文件成生成后立即部署网站
[-w, --watch]   监视文件变动

#发表草稿
hexo publish [layout]

#启动服务器  server
默认情况下启动服务器访问网址为：
http://localhost:4000/
[-p, --port]    重设端口
[-s, --static]  只是用静态文件
![](first/1564802677.jpg)

