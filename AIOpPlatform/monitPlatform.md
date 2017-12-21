# 监控系统之深度解析


## 概述



## 技术原理


## 生产案例


## 竞品分析



## 监控对象类别

|  对象层   |    类别    |     子类   |  版本 |
|------  |------      |:-----      |       |
|硬件层   |服务器       |            |    |
|硬件层   |交换机       |            |
|硬件层   |路由器       |            |     |
|硬件层   |防火墙       |            |     |
|硬件层   |UPS         |            |    |
|硬件层   |空调         |            |
|OS 层   | Linux      | Centos     |  7.2    |
|OS-内存 | Linux      | SUSE       |      |
|OS-CPU | Linux      | Ubuntu     |      |
|OS-负载 | Linux      | Redhat     |      |
|OS-磁盘 | Linux      |            |
|OS-网络 | windows    |            |
|OS-IO  | Unix       |            |
|OS-进程 | AIX        |            |
|虚拟化层 | KVM        |            |
|虚拟化层 | Docker     |            |
|虚拟化层 | Xen        |            |
|虚拟化层 | VMware     |            |
|虚拟化层 | OpenStack  |            |
|中间件层 | nginx      |            |
|中间件层 | Tomcat     |            |
|中间件层 | Apache     |            |
|中间件层 | JBoss      |            |
|中间件层 | Mysql      |            |
|中间件层 | Redis      |            |
|中间件层 | MongDB     |            |
|中间件层 | RabbitMQ   |            |
|中间件层 | LVS        |            |
|中间件层 | HAProxy    |            |
|中间件层 | Zookeeper  |            |
|应用层   | Java       |            |
|应用层   | Python     |            |
|应用层   | C          |            |
|应用层   |            |            |
|应用层   |            |            |
|应用层   |            |            |
|硬件层   |            |            |
|硬件层   |            |            |



## 健康模型


### 功能架构组成

*   **全局可视化展示系统**

* **各项指标图表**

* **历史健康基准线图表**

* **相关子系统监控数据的聚合分析器**




### 健康度算法





### OS 健康模型

*  **CPU**

*  **内存**

* **磁盘**

*  **网络**

* **I/O**

*  **负载**
   系统平均负载被定义为在特定时间间隔内运行队列中的平均进程数
   * **查看命令**
     * cat /proc/loadavg
     * top
     * w
     * tload
     * uptime
     
     
  * **参考**

    [Linux查看CPU信息[//proc/loadavg]](http://blog.csdn.net/zhouzhiwengang/article/details/44776645)

* **健康基线**

* **负载**
  <pre>
  [root@opendigest root]# uptime
　　7:51pm up 2 days, 5:43, 2 users, load average: 8.13, 5.90, 4.94
  </pre>
   一般来说只要每个CPU的当前活动进程数不大于3那么系统的性能就是良好的，如果每个CPU的任务数大于5，那么就表示这台机器的性能有严重问题。 对于 上面的例子来说，假设系统有两个CPU，那么其每个CPU的当前任务数为：8.13/2=4.065。这表示该系统的性能是可以接受的。



### 集群健康模型


### 业务健康模型





## 数据采集方案（方法协议）




## 引用



