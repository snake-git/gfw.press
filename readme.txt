
欢迎使用 GFW.Press 软件


一、客户端

请访问 http://gfw.press/GFW.Press.msi 下载客户端安装包

请访问 http://gfw.press 获取连接配置信息

配置填写完成，点击“确定”按钮

设置浏览器代理，地址： 127.0.0.1  端口： 3128


二、服务器

以 CentOS 为例:

第一步：下载 gfw.press

第二步：安装 JDK

yum install java-1.8.0-openjdk.x86_64 -y ;

第三步：安装代理软件

yum install squid -y ; 或者 yum instsall 3proxy -y ;

启动squid，启动命令squid -s （Ubuntu中是squid3 -s

第四步：修改连接帐号文件user.txt

每行表示一个帐号，由 端口号+空格+密码 组成，密码长度至少8位，必需包含大小写字母和数字

第五步：运行

chmod u+x /gfw.press/server.sh ;
/gfw.press/server.sh ;


请访问 http://twitter.com/chinashiyu 发表意见及建议

祝您好运

chinashiyu 

2016-04-16 23:49:00

