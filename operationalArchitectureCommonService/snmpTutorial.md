# SNMP简单网络管理协议学习路线







## [net-snmp 官网](http://www.net-snmp.org/)
Simple Network Management Protocol (SNMP) is a widely used protocol for monitoring the health and welfare of network equipment (eg. routers), computer equipment and even devices like UPSs. Net-SNMP is a suite of applications used to implement SNMP v1, SNMP v2c and SNMP v3 using both IPv4 and IPv6. The suite includes:

    Command-line applications to:
        retrieve information from an SNMP-capable device, either using single requests (snmpget, snmpgetnext), or multiple requests (snmpwalk, snmptable, snmpdelta).
        manipulate configuration information on an SNMP-capable device (snmpset).
        retrieve a fixed collection of information from an SNMP-capable device (snmpdf, snmpnetstat, snmpstatus).
        convert between numerical and textual forms of MIB OIDs, and display MIB content and structure (snmptranslate).
    A graphical MIB browser (tkmib), using Tk/perl.
    A daemon application for receiving SNMP notifications (snmptrapd). Selected notifications can be logged (to syslog, the NT Event Log, or a plain text file), forwarded to another SNMP management system, or passed to an external application.
    An extensible agent for responding to SNMP queries for management information (snmpd). This includes built-in support for a wide range of MIB information modules, and can be extended using dynamically loaded modules, external scripts and commands, and both the SNMP multiplexing (SMUX) and Agent Extensibility (AgentX) protocols.
    A library for developing new SNMP applications, with both C and perl APIs.

Net-SNMP is available for many Unix and Unix-like operating systems and also for Microsoft Windows. Note: Functionality can vary depending on the operating system. Please see the README files for information specific to your platform.

The documentation section contains detailed information on command line tools, installation, configuration etc.

If you are new to Net-SNMP or SNMP in general, then a good place to start is the tutorial section.

The download section contains the source code and binaries for various platforms.

Please see our project development pages located at Sourceforge as well.


## [SNMP百度百科](https://baike.baidu.com/item/SNMP/133378?fr=aladdin)


简单网络管理协议（SNMP），由一组网络管理的标准组成，包含一个应用层协议（application layer protocol）、数据库模型（database schema）和一组资源对象。该协议能够支持网络管理系统，用以监测连接到网络上的设备是否有任何引起管理上关注的情况。该协议是互联网工程工作小组（IETF，Internet Engineering Task Force）定义的internet协议簇的一部分。SNMP的目标是管理互联网Internet上众多厂家生产的软硬件平台，因此SNMP受Internet标准网络管理框架的影响也很大。SNMP已经出到第三个版本的协议，其功能较以前已经大大地加强和改进了。






## 安装及配置 SNMP  

    yum install net-snmp net-snmp-devel net-snmp-utils
    
    






查看snmpd服务启动的时长

    snmpget -v 2c -c public 127.0.0.1 SNMPv2-MIB::sysUpTime.0




查看系统启动时间

    snmpget -v 2c -c public 127.0.0.1 HOST-RESOURCES-MIB::hrSystemUptime.0
    

查看系统的磁盘空间使用情况

    snmpdf -v 2c -c public localhost
    
    

















































