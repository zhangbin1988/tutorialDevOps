# 2018详细工作日志







## 2018  Q1  



### 2018.01 


#### 2018.01.09

yum 安装 依赖不能解决 ， 报错

选择使用zabbix agent rpm 包方式安装 zabbix  agent 


查询rpm包的依赖关系
Posted on May 23, 2011 by alexu2595
# 查询未安装软件包的依赖关系
rpm -qRp vim-common-6.3.046-2.el4.1.x86_64.rpm

# 查询已安装软件包的依赖关系
rpm -qR vim-common-6.3.046-2.el4.1






#### 2018.01.08

生成秘钥

ssh-keygen -t rsa -C "youremail@example.com"

ansible 查看主机已授权的公钥
ansible -i hosts all   -m  command  -a "cat /root/.ssh/authorized_keys"



ansible -i hosts all   -m  shell  -a "mkdir /etc/yum.repos.d/bak"

ansible -i hosts all   -m  shell  -a "mv /etc/yum.repos.d/*.repo  /etc/yum.repos.d/bak/"








#### 2018.01.04 

* **为VNCsever**
 
 [nginx 文件服务器](http://blog.51cto.com/shower/1887206)
 
 
 autoindex on;
另外两个参数最好也加上去:
autoindex_exact_size off;
默认为on，显示出文件的确切大小，单位是bytes。
改为off后，显示出文件的大概大小，单位是kB或者MB或者GB

autoindex_localtime on;
默认为off，显示的文件时间为GMT时间。
注意:改为on后，显示的文件时间为文件的服务器时间
但是如果有中文目录的话会出现乱码问题，所以还需要在下面添加这一句：
charset utf-8,gbk;

 [nginx设置目录浏览及中文乱码问题解决](https://wangheng.org/nginx-set-directory-browsing-and-solve-the-problem-of-chinese-garbled.html)
 
 [nginx设置目录浏览及中文乱码问题解决](http://blog.csdn.net/w657395940/article/details/50241771)
 
 
 [vnc 远程访问主机vnc 下载](http://www.ihacksoft.com/vnc-realvnc-5.html)
 
 
 [windows下使用vnc viewer远程连接Linux桌面 ](http://blog.51cto.com/nameyjj/582965)
 [下载VNC](https://pan.baidu.com/share/link?shareid=405018&uk=321447710&errno=0&errmsg=Auth%20Login%20Sucess&&bduss=&ssnerror=0&traceid=)
 
 **  切换系统语言   
  *  [CentOS 7 切换系统语言](https://www.yanning.wang/archives/244.html)
 
 


#### 2018.01.03 

**为Centos安装图形界面**



