# gateOne教程


## 概述

Gate One is a web-based terminal emulator and SSH client that requires no browser plugins and includes many unique and advanced features.

What is Gate One?
This is the official Docker repo for Gate One--a web based terminal emulator and SSH client (and soon to support X11). 
The first time you 'docker run' the liftoff/gateone image it will automatically update itself with the latest code from Github.

Inside the image Gate One is configured to run as the root user
(due to a bug in Docker; see https://github.com/docker/docker/issues/5892) and listen on port 8000. 
It is also configured to use /gateone/logs for logging and /gateone/users for the user_dir. 
The settings_dir is still at the usual /etc/gateone/conf.d location and SSL certificates
(which will be generated automatically the first time you run the image) are stored in /etc/gateone/ssl/.


## 技术原理


## 部署安装

[GateOne Web SSH环境搭建](https://www.jianshu.com/p/2f66f7242788)

[应用嵌入GateOne以及SSH自动登陆](https://www.jianshu.com/p/b8123a8178de)




## 生产案例


## 最佳实践

[gateone Docker镜像](https://hub.docker.com/r/liftoff/gateone/)

## 引用

https://pypi.python.org/pypi/gateone/1.2.0

https://liftoff.github.io/GateOne/index.html

http://liftoffsoftware.com/Products/GateOne

https://github.com/liftoff/GateOne



