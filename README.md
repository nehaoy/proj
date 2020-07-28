# proj
记录我的一些应用工程的例子。


一、配置多个MySQL服务
方法：
下载解压版MySQL后，
1、复制MySQL整个目录到本地，如D:\mysql-5.7.27-2019，修改my.ini，更改端口号port 及目录basedir,datadir，如下：
[mysqld]
port=3307
basedir=D:\mysql-5.7.27-2019
datadir=D:\mysql-5.7.27-2019\data

2、以管理员身份运行cmd，进入：D:\mysql-5.7.27-2019\bin
D:\mysql-5.7.27-2019\bin>mysqld install "mysql-2019" --defaults-file="D:\mysql-5.7.27-2019\my.ini"
Service successfully installed.

完成。

二、


三、
