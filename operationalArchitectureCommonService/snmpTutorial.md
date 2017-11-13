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

