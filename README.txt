1、启动后端jar服务   
     java -jar netty-push-0.0.1-SNAPSHOT.jar
     占用端口： http：8090      websoket：58080
     
    注：需要下载jdk，用来开启jar后端服务，建议版本：jdk-8u181-windows-x64.exe 【高版本启动项目会报错】
           下载地址： 我的网盘

2、打开client1、client2客户端
     两客户端都开启websoket之后，客户1，点击发送消息，客户2页面会多出一条websoket服务器发给客户2的信息。