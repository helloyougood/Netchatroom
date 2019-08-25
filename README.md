# Netchatroom
电子科大网络软件设计课程项目代码
项目：即时通信系统 - 聊天室
基本要求：
服务器实现同时接入多个客户端
结合项目三，每个客户通过认证，并各自使用不同的帐号
所有用户的帐号和口令记录在服务器的文件里
客户端可以看到当前接入用户的列表
结合项目二，客户端可以选择与某个指定用户进行聊天，或者选择将数据发送给所有客户
所有的聊天数据要经过服务器中转
结合项目三，客户可以上传或下载文件
两个客户之间可以通过服务器的中转在线相互传递文件，即不是一边先上传，完毕后，另一边再下载，而是通过服务器代理中转的“端到端”传输。——类似QQ的在线传输
客户机能够接收服务器的广播命令

扩展要求
具有用户注册功能，新用户建立自己的上传、下载目录
客户端有图形化界面。
能够拖动文件到客户端，直接上传
客户端连接后，自动下载服务器共享目录和独享目录中的文件。

该项目主要实现了基本任务需求。
