# 基于psutil打造的可视化监控系统




## 需求分析


## 系统的概要设计


## 系统详细设计



## 开发计划 



## 测试方案



## 部署上线

### 环境要求

### 部署方案

### 操作说明

### 常见问题的处理方案




## [psutil 概述](https://github.com/giampaolo/psutil/)
. psutil是一个跨平台库（http://code.google.com/p/psutil/），能够轻松实现获取系统运行的进程和系统利用率（包括CPU、内存、磁盘、网络等）信息。
它主要应用于系统监控，分析和限制系统资源及进程的管理。它实现了同等命令行工具提供的功能，如ps、top、lsof、netstat、ifconfig、who、df、
kill、free、nice、ionice、iostat、iotop、uptime、pidof、tty、taskset、pmap等。
目前支持32位和64位的Linux、Windows、OS X、FreeBSD和Sun Solaris等操作系统，

Cross-platform lib for process and system monitoring in Python 
psutil (process and system utilities) is a cross-platform library for retrieving information on running processes and system utilization (CPU, memory, disks, network, sensors) in Python. It is useful mainly for system monitoring, profiling and limiting process resources and management of running processes. It implements many functionalities offered by UNIX command line tools such as: ps, top, lsof, netstat, ifconfig, who, df, kill, free, nice, ionice, iostat, iotop, uptime, pidof, tty, taskset, pmap. psutil currently supports the following platforms:

    Linux
    Windows
    OSX,
    FreeBSD, OpenBSD, NetBSD
    Sun Solaris
    AIX

...both 32-bit and 64-bit architectures, with Python versions from 2.6 to 3.6. PyPy is also known to work.


http://www.cnblogs.com/liu-yao/p/5678157.html


## psutil包使用详解

### [psutil教程--廖雪峰](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/001511052957192bb91a56a2339485c8a8c79812b400d49000)





## 开源项目

**Glances is a cross-platform monitoring tool which aims to present a maximum of information in a minimum of space through a curses or Web based interface. It can adapt dynamically the displayed information depending on the user interface size.**
* [glances](https://nicolargo.github.io/glances/) <br>
  * [源码](https://github.com/nicolargo/glances)
  * [用户手册&帮助文档](http://glances.readthedocs.io/en/latest/index.html)
  * [pip--安装包](https://pypi.python.org/pypi/Glances)

**psdash is a system information web dashboard for linux using data mainly served by psutil - hence the name.**
* [psdash](https://psutil.readthedocs.io/en/latest/) <br>
   * [源码](https://github.com/Jahaja/psdash)
   * [pip--安装包](https://pypi.python.org/pypi/psdash/0.6.2)



<pre>
[root@localhost pyhonDev]# psdash --help 
usage: psdash [-h] [-l path] [-b host] [-p port] [-d] [-a]
              [--register-to host:port] [--register-as name]

psdash 0.6.2 - system information web dashboard

optional arguments:
  -h, --help            show this help message and exit
  -l path, --log path   log files to make available for psdash. Patterns (e.g.
                        /var/log/**/*.log) are supported. This option can be
                        used multiple times.
  -b host, --bind host  host to bind to. Defaults to 0.0.0.0 (all interfaces).
  -p port, --port port  port to listen on. Defaults to 5000.
  -d, --debug           enables debug mode.
  -a, --agent           Enables agent mode. This launches a RPC server, using
                        zerorpc, on given bind host and port.
  --register-to host:port
                        The psdash node running in web mode to register this
                        agent to on start up. e.g 10.0.1.22:5000
  --register-as name    The name to register as. (This will default to the
                        node's hostname)
</pre>








## 引用 



https://github.com/giampaolo/psutil/

https://nicolargo.github.io/glances/

https://github.com/nicolargo/glances

https://pypi.python.org/pypi/psutil

http://psutil.readthedocs.io/en/latest/

https://github.com/giampaolo/psutil

https://github.com/showersh/psdash/blob/master/README.md

http://tiarno.github.io/psmonitor/

https://reachtim.com/articles/psutil-and-mongodb-for-system-monitoring.html

http://docs.celeryproject.org/en/3.0/userguide/monitoring.html

https://github.com/hakanzy/django-system-monitor



