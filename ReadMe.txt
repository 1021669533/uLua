﻿项目开源免费，求上面点星支持(star ^o^)

本框架工程基于Unity 4.6.2/5.0 + cstolua构建，网上插件版本以本工程导出。

有问题请加：ulua技术交流1群 341746602(已满)、请加2群：469941220

支持平台：PC/MAC/Android(armv7-a + Intel x86)/iOS(armv7 + arm64)/
	  WP8(SimpleFramework_WP_v0.1.1 (nlua))/

视频教程地址 http://pan.baidu.com/s/1gd8fG4N
游戏案例地址 http://www.ulua.org/showcase.html
框架详细介绍 http://bbs.ulua.org/default.asp?cateID=4

//-------------2015-10-17-------------
(1)编译底层库使其支持在安卓、iOS进行Lua真机调试。
PS:现在可调试平台包括WIN/MAC/LINUX/iOS/Android全平台。
   真机调试方法：要调试的lua需要处于打开状态。
   第一个lua脚本里面 加上 require("mobdebug").start('192.168.217.112') 。
   感谢大神tangram发现并亲测。

//-------------2015-10-11-------------
(1)首次提交以uLua_v1.23为基础，修复03反射例子。
(2)Wrap文件列表从BindLua.cs里面独立到WrapFile.cs。