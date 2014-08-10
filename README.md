netty-test
==========

netty study little  demo

com.galaxy.netty.server101 server :return time

com.galaxy.netty.client101 client :query time

server101,client101 会有粘包的风险
--------------------------------------------------
com.galaxy.netty.server102 server :return time

com.galaxy.netty.client102 client :query time
server102,client102 模拟server端和client端出现的粘包问题

--------------------------------------------------
com.galaxy.netty.server103 server :return time

com.galaxy.netty.client103 client :query time
server103,client103 利用netty自带的LineBasedFrameDecoder解码器解决出现的粘包问题

--------------------------------------------------

com.galaxy.netty.http

实现一个简单的http服务器，com.galaxy.netty.http.HttpStaticFileServer.main()启动后，
能够在浏览器查看当前项目的目录结构以及代码

