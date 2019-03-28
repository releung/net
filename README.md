# Internet

本课程从实践入手循序渐进，以Linux系统环境和Linux内核源代码为例，将Linux网络相关命令用法、Socket网络编程、TCP协议、IP协议及路由表、ARP协议及ARP缓存、二层交换网络的学习转发和过滤数据库等互联网架构的关键环节一一解析，并通过MenuOS实验系统进行代码跟踪分析。最终理解分析打开一个网页背后互联网的工作过程，其中重点分为三个抽象层次：一是便于人类理解的记忆的编址方式DNS Naming；二是便于全球定位编址和路由的IP Networking；三是便于局域网中实际完成数据交换传输的Layer 2 Switching；同时在理解互联网体系结构的基础上探寻它的历史演化渊源，乃至发现它背后的设计哲学，解读未来网络的演进方向。

## 互联网概述
* 1.1 课程内容简介
* 1.2 网络协议基础
* 1.3 上网浏览网页背后的网络通信过程
* 1.4 实验环境安装配置
* 1.5 网络相关命令

## Socket网络编程

* 2.1 编译、构建和调试
* 2.2 Socket接口
* 2.3 UDP范例代码
* 2.4 TCP范例代码

## TCP协议

* 3.1 TCP协议概述
* 3.2 Linux网络协议栈源代码简介
* 3.3 Linux系统的编译、构建和调试
* 3.4 TCP协议源代码分析

## IP协议及路由表

* IP协议基础
* 路由表 
* 路由转发举例
* IP协议栈源代码解析
* 路由协议简介
* 网络层数据传输路径解析

## ARP协议及ARP缓存

* ARP协议基础
* ARP解析的过程
* ARP解析在网络传输过程中的作用
* ARP协议栈源代码解析

## 二层交换网络及转发过滤数据库

* 以太网基础
* 交换机的学习、转发和过滤数据库
* 常见二层协议
* 数据链路层在Linux网络协议栈中的一些关键代码分析

## DNS协议及域名存储与解析

* DNS协议基础
* DNS域名的存储
* DNS域名解析过程分析

## 互联网架构设计背后的渊源

* 互联网架构设计的最初动机与核心目标
* 互联网架构设计的具体目标及背后重要权衡

