# cyftpd
Away from VSFTPD...Will be a better choice...

## 为什么要创建这个项目

深受vsftpd的配置痛苦,并且必须绑定访问地址的脑残设定...
决定设计一个更简单的ftpServer..


## 环境搭建..
我们需要一下的这些包

1. 程序本身(鬼都知道).
2. python3的版本
	* 不清楚的可以使用`python -V 去看一下版本`
	* 如果是2.x版本的话看看有没有python3这个命令
3. pyftpdlib的库-使用pip安装即可
4. 强烈建议开启的ssl..所以安装.默认如果没有配置会自动给你配置.PyOpenSSL的库-使用pip安装即可
5. 如果用户名等信息存储在mysql里面.请安装pymysqld库

