jQuery教程

参考地址：http://www.w3school.com.cn/jquery/index.asp
https://www.cnblogs.com/witkeydu/p/8526089.html

jQuery框架-1.基础知识

jQuery简介

jQuery，顾名思义是JavaScript和查询（Query），jQuery是免费、开源的。
它可以简化查询DOM对象、处理事件、制作动画、处理Ajax交互过程且兼容多浏览器的javascript库，核心理念是write less,do more(写得更少,做得更多)。


由于 jQuery 是为处理 HTML 事件而特别设计的，那么当您遵循以下原则时，您的代码会更恰当且更易维护：
把所有 jQuery 代码置于事件处理函数中
把所有事件处理函数置于文档就绪事件处理器中
把 jQuery 代码置于单独的 .js 文件中
如果存在名称冲突，则重命名 jQuery 库

2018-03-23添加如下内容：
一、git修改文件后，提交到远程仓库
1.git status    查看git是否有修改内容需要提交
2.git add README.txt   指向需要提交的内容文件
3.git commit -m "这里写提交说明" 提交到本地库
4.git push origin master 提交到远程仓库
5.git pull 刷新本地库