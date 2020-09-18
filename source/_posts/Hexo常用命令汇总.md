---
title: Hexo常用命令汇总
date: 2020-09-16 13:53:38
tags: Hexo
---

#### 1、**hexo s**

启动本地服务器，用于预览主题。默认地址： http://localhost:4000/

- hexo s 是 hexo server 的缩写；
- 支持本地修改同步预览，如有报错，会在命令行输出，很适合本地调试； 
- 对 Hexo 根目录 _config.yml 的修改，需要重启本地服务器后才能预览效果。

#### 2、**hexo new**

hexo new "Hexo常用命令汇总"

- 新建一篇标题为 Hexo常用命令汇总 的文章
- 文章标题可以在对应 md 文件里改，新建时标题可以写的简单些。

#### 3、**hexo g**

生成网站静态文件到默认设置的 public 文件夹。

- hexo g 是 hexo generate 的缩写；
- 新建完文章之后，如要本地查看效果，要执行这条；
- 便于查看网站生成的静态文件或者手动部署网站。

#### 4、**hexo d**

自动生成网站静态文件，并部署到设定的仓库。

- hexo d 是 hexo deploy 的缩写；
- 部署过去的只有public文件夹。

#### 5、**hexo clean**

清除缓存文件 db.json 和已生成的静态文件 public 。

- 无备份时不要轻易尝试此命令哦。

#### 6、**hexo new page pagename**

新建一个标题为pagename的页面，默认地址为主页地址/pagename/

- 标题可以是中文，但是推荐英文；
- 页面不会出现在首页文章列表和归档中，也不支持设置分类和标签。