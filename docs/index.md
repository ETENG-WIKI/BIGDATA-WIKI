#文档说明


文档使用 gitbook 书写发布,教程如下, 书写之后提交到githup 即可自动发布到gitbook


# gitbook quick start 


官方Docs: http://toolchain.gitbook.com/  

官方github: https://github.com/GitbookIO/gitbook  


中文教程: 

http://www.chengweiyang.cn/gitbook/index.html  

http://colobu.com/2014/10/09/gitbook-quickstart  


安装gitbook

	npm install gitbook-cli -g


初始化

	$ gitbook init

启动代理服务

	gitbook serve

创建book.json

	{
    "root": "./docs",
    "title": "大数据WIKI",
    "description": "大数据WIKI",
    "author": " robin gao "
    }

创建docs目录

在docs中创建文件 README.md 和 SUMMARY.md

SUMMARY.md 配置目录 

	# Summary

	* [Home](index.md)
	* [大数据开源组件选型]()
	* [离线日志处理流程]()
	* [大数据平台环境部署amb]()
	* [大数据开源组件简单应用]()
		* [hadoop]()
