---
title: Hexo本地目录指南
date: 2020-09-16 15:02:49
tags: Hexo
---

我存放Hexo的目录叫myblog，然后来看一下安装好后的目录树：

```text
第一层：
	.deploy_git
	node_modules
	public
	scaffolds
	source
	themes
	
	_config.yml
	db.json
	package.json
	package-lock.json
```

### .deploy_git

​	根据hexo d后部署的网站，根据public修改。

### node_modules

​	这个目录用来存放安装过的各类依赖包，新安装的依赖包也会自动存储在这里。

### public

​	网站目录。当执行过hexo g命令后，将source下的文章等，打包渲染生成html页面，存放在public下。另外css与js文件也存放在这里，归档及标签分类目录也保存在此。

### scaffold

​	存放各类模板的目录，当你新建文章时，自动按照这里的模板创建空白MD文件。

​	默认有3类：page（页面）、post（文章）、draft（草稿）

### source

​	资源目录，主要存放文章、页面、草稿、图片等，可以通过直接在这里修改文章，然后hexo g打包，hexo d部署到服务器。

### themes

​	就如名字所说，存放主题的目录。

​	可以去官方给的地址：https://hexo.io/themes/ 找自己喜欢的主题，或者直接在GitHub上找，一个主题对应一个完整的文件夹，默认主题叫landscape。

​	对应更换主题时，需要修改配置参数里的themes，名字与文件夹同步。另外修改主题语言是，配置文件中可更换的语言范围根据皮肤主题下的language目录中存放的文件名确定。

### _config_yml

​	配置文件，使用yaml语法，参考：https://my.oschina.net/u/1861837/blog/526142，网站的很多关键信息及参数在此修改存储，远程备份很重要。参数及配置方法可以参考官方文档：https://hexo.io/zh-cn/docs/configuration.html，有简中版本，很好操作。

### package.json

​	写有Hexo和依赖插件的版本信息







参考文档

1、[简单认识Hexo的目录结构](https://segmentfault.com/a/1190000018237272)

2、[建站](https://hexo.io/zh-cn/docs/setup.html)

