---
layout: post
title: "iOS应用崩溃日志揭秘"
date: 2013-11-11 10:49
comments: true
categories: 
---
自己模拟器和真机上测试都没有问题，但store上用户评论存在闪退问题，于是通过这篇[博文](http://blog.devtang.com/blog/2013/07/24/use-crashlytics/)更新了一个版本，新加入[crashlytics](http://try.crashlytics.com)工具收集用户的crash log，但是等待审核迟迟不能通过，于是就打算自己手动去分析下已有的崩溃日志报告，打开这些`.crash`文件，对于一个菜鸟来说这报告看起来像天书，于是Google了一下，结果第一条就找到入手点，参考[iOS应用崩溃日志揭秘](http://www.raywenderlich.com/zh-hans/30818/ios应用崩溃日志揭秘)，一步一步按着教程来，了解崩溃日志的内容。