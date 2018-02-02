# [部署adminset](https://github.com/guohongze/adminset/blob/master/install/)教程

## 环境信息

|名称|版本信息|安装路径|||
|------|------|------|------|------|
|Centos|------|------|------|------|
|Mysql|------|------|------|------|
|Nginx|------|------|------|------|
|webssh|------|------|------|------|
|ssh|------|------|------|------|
|celery|------|------|------|------|
|adminset|------|/var/opt/adminset|------|------|


## 部署概述

### 服务器端部署

* **安装路径**
  * /var/opt/adminset/main
    * /var/opt/adminset/main/pid
  * /var/opt/adminset/data
    * /var/opt/adminset/data/scripts
    * /var/opt/adminset/data/ansible/playbook
    * /var/opt/adminset/data/ansible/roles
  * /var/opt/adminset/config
    * /var/opt/adminset/config/ssh
  * /var/opt/adminset/logs


### 客户端部署



## 详细操作步骤



### [服务器端部署](https://github.com/guohongze/adminset/blob/master/install/server/server_install.sh)

关闭 selinux 

安装依赖

`yum install -y gcc python-pip expect python-devel ansible smartmontools dmidecode libselinux-python`




### [客户端部署]()








## 引用


[服务器端部署脚本](https://github.com/guohongze/adminset/blob/master/install/server/server_install.sh)

[]()

[]()
