# [mariadb](https://mariadb.com/)教程

## 概述



## 部署


## 生产案例


### [为 MariaDB 配置远程访问权限](https://mariadb.com/kb/zh-cn/configuring-mariadb-for-remote-client-access/)

/etc/my.conf

<pre>
  bind-address = 0.0.0.0

  GRANT ALL PRIVILEGES ON *.* to 'root'@'10.90.85.22' identified by '123456';  
</pre>

[为 MariaDB 配置远程访问权限](https://mariadb.com/kb/zh-cn/configuring-mariadb-for-remote-client-access/)

[远程连接MySQL(MariaDB)数据库 ](http://blog.csdn.net/lnboxue/article/details/74275928)

[配置mysql允许远程连接的方法](https://www.cnblogs.com/linjiqin/p/5270938.html)





## 引用

