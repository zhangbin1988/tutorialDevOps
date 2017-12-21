# Asible教程

标签（空格分隔）： yaml ansible 

---

[TOC]



## 学习目标

* 了解ansible playbook的应用场景及优势
* playbook的基本语法
* 学习简单的playbook实战案例


## Ansible&playbook概述

**高效应用部署、系统管理、迅速消除复杂性**

* 背景
  * 身处复杂 IT 环境，即便一个很小的任务都要花费不少时间才能完成。而错综复杂的系统环境更是让开发、部署和维护工作难以顺利展开。与此同时，伴随着业务需求的复杂性与日俱增，IT 团队面对诸多管理、可用性和成本挑战步履维艰。

* Ansible， 一款简单、无代理 IT 自动化技术，可有效改善您的当前业务流程和应用迁移，以优化业务操作；同时帮助您的企业采用单个编程语言，轻松实现 DevOps（开发运营）业务实践。

* Playbook是Ansible的配置，部署和编排语言。 他们可以描述您希望远程系统执行的策略，或一般IT流程中的一组步骤。
* Playbooks是一个非常简单的配置管理和多机器部署系统的基础，不像任何已经存在的那样，而且非常适合部署复杂的应用程序。

* 每个playbook由一个或多个“plays”组成。

* **功能和优势**
  * IT自动化
  * 化繁为简
  * 减少重复操作
  * 轻松入门
  * 社区动力


  playbook 在ansible 功能架构中作用 
* 开源、自动化平台
* 无代理
* 免费下载和使用
* 配置管理
* 应用部署
* 任务自动化

![ansible架构](http://s3.51cto.com/wyfs02/M02/65/E1/wKioL1UrMIaAShvsAAIah00MZoE168.jpg)

![]()

### 需要的知识储备

* **YAML**
* **模块**
* Jinja2
* **inventory**
* **hosts**
* lookups
* conditionals


## 语法详解

### playbook变量使用

### playbook使用环境变量

### playbook的条件循环

#### 条件判断

#### 循环



### 


<pre>
    - hosts: web
      tasks:
        - name: Installs apache web server
          apt: pkg=apache2 state=installed update_cache=true
</pre>

![](http://jedelman.com/img/a4n1.png)

**执行过程**

![执行过程](http://s3.51cto.com/wyfs02/M01/53/A7/wKiom1Rsx2uQYJZ5AAJplY08vOQ976.jpg)


## 教程


[PlaybookIn_tro](http://docs.ansible.com/ansible/latest/playbooks_intro.html)

[Ansible6：Playbook简单使用](https://www.cnblogs.com/paul8339/p/6159227.html)

* Target section
* Variable section
* Task section
* Handler section

**目录层**

* var 变量层
* tasks 任务层
* handlers 触发条件
* files 文件
* template 模板


**[Best Practices](http://docs.ansible.com/ansible/latest/playbooks_best_practices.html)**

* Content Organization
  * Directory Layout
  * Alternative Directory Layout
  * Use Dynamic Inventory With Clouds
  * How to Differentiate Staging vs Production
  * Group And Host Variables
  * Top Level Playbooks Are Separated By Role
  * Task And Handler Organization For A Role
  * What This Organization Enables (Examples)
  * Deployment vs Configuration Organization
* Staging vs Production
* Rolling Updates
* Always Mention The State
* Group By Roles
* Operating System and Distribution Variance
* Bundling Ansible Modules With Playbooks
* Whitespace and Comments
* Always Name Tasks
* Keep It Simple
* Version Control
* Variables and Vaults







## 生产案例

### [自动部署Nginx](https://galaxy.ansible.com/geerlingguy/nginx/)

### 一键部署ELK

### 一键部署Zabbix

## 引用
Ansible 开发专题总揽
http://www.jianshu.com/p/667dabe96f04

http://www.jianshu.com/p/8b17779febf3
Ansible 专题文章总揽
http://www.jianshu.com/p/c56a88b103f8


https://ansible-tran.readthedocs.io/en/latest/

http://docs.ansible.com/ansible/latest/playbooks_intro.html

http://www.yaml.org/

http://www.yaml.org/spec/1.2/spec.html

https://www.redhat.com/zh/technologies/management/ansible


https://galaxy.ansible.com/explore#/

http://www.cnblogs.com/chenxianpao/p/7360349.html

https://serversforhackers.com/c/an-ansible-tutorial

