### 项目概述

该项目是一个简单的webServer，使用 epoll + threadpool 实现，支持GET、POST方法，可以实现html、jpg、png、ico、MP3、js、css等文件的解析.

### 使用说明
主要功能有

- 在线播放音乐和下载视频(如果在vedio-center添加了视频的前提下)
- 点击登录注册,可以提交用户输入信息到CGI程序中处理并将指定结果返回给浏览器!

以2345端口为例，终端输入：

make

./main 127.0.0.1 2345

打开浏览器，输入：

127.0.0.1:2345

即可看到网页显示。

### 版本说明

该版本是基于epoll+线程池实现的高并发稳定版服务器
<a href="https://blog.csdn.net/qq_41681241/article/details/88584729">设计实现</a>
    
