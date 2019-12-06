# IT 技术图谱

> IT 技术之路 —— 我秃了也变强了

<!-- TOC -->

- [数据结构](#数据结构)
  - [数组](#数组)
  - [栈](#栈)
    - [队列](#队列)
    - [链表](#链表)
    - [树](#树)
    - [普通树](#普通树)
    - [二叉树](#二叉树)
    - [红黑树](#红黑树)
    - [图](#图)
    - [堆](#堆)
    - [Hash 表](#hash-表)
- [算法](#算法)
  - [查找](#查找)
    - [线性表的查找](#线性表的查找)
    - [哈希表的查找](#哈希表的查找)
  - [排序](#排序)
- [操作系统](#操作系统)
  - [Linux](#linux)
  - [Windows](#windows)
  - [Mac](#mac)
- [网络通信](#网络通信)
  - [网络分层](#网络分层)
    - [物理层](#物理层)
    - [链路层](#链路层)
    - [网络层](#网络层)
    - [传输层](#传输层)
    - [应用层](#应用层)
  - [协议](#协议)
    - [HTTP](#http)
    - [DNS](#dns)
    - [TCP](#tcp)
    - [UDP](#udp)
    - [ICMP](#icmp)
    - [WebSocket](#websocket)
    - [CDN](#cdn)
- [数据库](#数据库)
- [大数据](#大数据)
- [安全](#安全)
- [分布式](#分布式)
  - [负载均衡](#负载均衡)
  - [缓存](#缓存)
  - [消息队列](#消息队列)
  - [分布式锁](#分布式锁)
  - [分布式会话](#分布式会话)
  - [分布式存储](#分布式存储)
  - [分布式 ID](#分布式-id)
  - [分布式事务](#分布式事务)
  - [分库分表](#分库分表)
- [架构](#架构)
  - [设计模式](#设计模式)
  - [设计思想](#设计思想)
    - [重构](#重构)
- [运维](#运维)
- [软件工程](#软件工程)
- [编程](#编程)
  - [脚本](#脚本)
  - [前端](#前端)
- [Java](#java)
  - [Java 核心技术](#java-核心技术)
  - [Java Web 技术](#java-web-技术)
- [框架](#框架)
  - [Spring](#spring)
  - [Spring Boot](#spring-boot)
- [工具](#工具)
  - [Git](#git)
  - [正则](#正则)
  - [UML](#uml)
  - [Gitbook](#gitbook)
- [资源](#资源)

<!-- /TOC -->

## 数据结构

### 数组

[数组](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/data-structure/array.md)

### 栈

[栈](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/data-structure/stack.md)

#### 队列

[队列](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/data-structure/queue.md)

#### 链表

[链表](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/data-structure/list.md)

#### 树

#### 普通树

[树](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/data-structure/tree/tree.md)

#### 二叉树

[二叉树](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/data-structure/tree/binary-tree.md)

#### 红黑树

[红黑树](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/data-structure/tree/red-black-tree.md)

#### 图

[图](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/data-structure/graph.md)

#### 堆

[堆](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/data-structure/heap.md)

#### Hash 表

[散列表](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/data-structure/hash.md)

## 算法

### 查找

#### 线性表的查找

[线性表的查找](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/search/linear-list-search.md)

#### 哈希表的查找

[哈希表的查找](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/search/hash-search.md)

### 排序

[细说排序算法](https://github.com/dunwu/algorithm-tutorial/blob/master/docs/algorithm/sort.md)

冒泡排序、快速排序、直接插入排序、希尔排序、简单选择排序、堆排序、归并排序、基数排序 全家桶。

## 操作系统

### Linux

内容已整理为 [Linux 教程 📚](https://dunwu.github.io/linux-tutorial/)

### Windows

- [Windows 常用技巧总结](https://github.com/dunwu/blog/blob/master/source/_posts/os/windows.md)

### Mac

- [Mac 常用技巧总结](https://github.com/dunwu/blog/blob/master/source/_posts/os/mac.md)

## 网络通信

[计算机网络指南](https://github.com/dunwu/blog/blob/master/source/_posts/communication/network-guide.md) - 关键词：核心概念、拓扑结构、作用范围、性能指标、体系结构

### 网络分层

#### 物理层

[计算机网络之物理层](https://github.com/dunwu/blog/blob/master/source/_posts/communication/network-physical.md) - 关键词：调制、解调、数字信号、模拟信号、通信媒介、信道复用

#### 链路层

分层

- [计算机网络之链路层](https://github.com/dunwu/blog/blob/master/source/_posts/communication/network-data-link.md) - 关键词：点对点信道、广播信道、`PPP`、`CSMA/CD`、局域网、以太网、`MAC`、适配器、集线器、网桥、交换机

#### 网络层

- [计算机网络之网络层](https://github.com/dunwu/blog/blob/master/source/_posts/communication/network-network.md) - 关键词：`IP`、`ICMP`、`ARP`、路由

#### 传输层

- [计算机网络之传输层](https://github.com/dunwu/blog/blob/master/source/_posts/communication/network-transport.md) - 关键词：`UDP`、`TCP`、滑动窗口、拥塞控制、三次握手

#### 应用层

- [计算机网络之应用层](https://github.com/dunwu/blog/blob/master/source/_posts/communication/network-application.md) - 关键词：`HTTP`、`DNS`、`FTP`、`TELNET`、`DHCP`

### 协议

#### HTTP

[网络协议之 HTTP](https://github.com/dunwu/blog/blob/master/source/_posts/communication/http.md)

#### DNS

[网络协议之 DNS](https://github.com/dunwu/blog/blob/master/source/_posts/communication/dns.md)

#### TCP

[网络协议之 TCP](https://github.com/dunwu/blog/blob/master/source/_posts/communication/tcp.md)

#### UDP

[网络协议之 UDP](https://github.com/dunwu/blog/blob/master/source/_posts/communication/udp.md)

#### ICMP

[网络协议之 ICMP](https://github.com/dunwu/blog/blob/master/source/_posts/communication/icmp.md)

#### WebSocket

[网络协议之 WebSocket](https://github.com/dunwu/blog/blob/master/source/_posts/communication/websocket.md)

#### CDN

[网络通信之 CDN](https://github.com/dunwu/blog/blob/master/source/_posts/communication/cdn.md)

## 数据库

## 大数据

TODO

## 安全

[常见安全手段基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/security-theory.md)

## 分布式

- [系统原理面试题](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/system-theory-interview.md)
- [分布式基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/distributed-base-theory.md)

### 负载均衡

- [负载均衡基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/load-balance-theory.md)

### 缓存

- [缓存基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/cache-theory.md)

### 消息队列

- [消息队列基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/mq-theory.md)

### 分布式锁

- [分布式锁基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/distributed-lock-theory.md)

### 分布式会话

- [分布式会话基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/distributed-session-theory.md)

### 分布式存储

- [分布式存储基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/distributed-storage-theory.md)

### 分布式 ID

- [分布式 ID 基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/distributed-id-theory.md)

### 分布式事务

- [分布式事务基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/distributed-transaction-theory.md)

### 分库分表

- [分库分表基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/design/theory/sharding-theory.md)

## 架构

### 设计模式

### 设计思想

- [系统架构面试题](https://github.com/dunwu/blog/blob/master/source/_posts/design/architecture/system-architecture-interview.md)
- [系统架构概述](https://github.com/dunwu/blog/blob/master/source/_posts/design/architecture/system-architecture-overview.md)
- [高性能架构](https://github.com/dunwu/blog/blob/master/source/_posts/design/architecture/high-performance-architecture.md)
- [高可用架构](https://github.com/dunwu/blog/blob/master/source/_posts/design/architecture/high-availability-architecture.md)
- [伸缩性架构](https://github.com/dunwu/blog/blob/master/source/_posts/design/architecture/scalable-architecture.md)
- [扩展性架构](https://github.com/dunwu/blog/blob/master/source/_posts/design/architecture/extensible-architecture.md)
- [安全性架构](https://github.com/dunwu/blog/blob/master/source/_posts/design/architecture/secure-architecture.md)
- [大型系统核心技术](https://github.com/dunwu/blog/blob/master/source/_posts/design/architecture/system-core-technologies.md)

#### 重构

- [代码的坏味道和重构](https://github.com/dunwu/blog/blob/master/source/_posts/design/refactor/代码的坏味道和重构.md)
- [代码坏味道之代码臃肿](https://github.com/dunwu/blog/blob/master/source/_posts/design/refactor/代码坏味道之代码臃肿.md)
- [代码坏味道之滥用面向对象](https://github.com/dunwu/blog/blob/master/source/_posts/design/refactor/代码坏味道之滥用面向对象.md)
- [代码坏味道之变革的障碍](https://github.com/dunwu/blog/blob/master/source/_posts/design/refactor/代码坏味道之变革的障碍.md)
- [代码坏味道之非必要的](https://github.com/dunwu/blog/blob/master/source/_posts/design/refactor/代码坏味道之非必要的.md)
- [代码坏味道之耦合](https://github.com/dunwu/blog/blob/master/source/_posts/design/refactor/代码坏味道之耦合.md)

## 运维

TODO

## 软件工程

TODO

## 编程

- [如何学习一门编程语言](https://github.com/dunwu/blog/blob/master/source/_posts/coding/programming-guide.md)

### 脚本

- [一篇文章让你彻底掌握 Python](https://github.com/dunwu/blog/blob/master/source/_posts/coding/python.md)
- [一篇文章让你彻底掌握 Shell](https://github.com/dunwu/blog/blob/master/source/_posts/coding/shell.md)

### 前端

> 内容已整理为 [前端编程教程 📚](https://dunwu.github.io/frontend-tutorial/)

## Java

> 内容已整理为 [Java 教程 📚](https://turnon.gitee.io/java-tutorial/) - 本人作为一名 Java 程序员，十年的技术积累，汇总与此。

### Java 核心技术

> 内容已整理为 [JavaCore 教程 📚](https://dunwu.github.io/javacore/) - 内容包含：Java 基础特性、Java 高级特性、Java 并发、JVM、Java IO 等。

### Java Web 技术

> 内容已整理为 [JavaWeb 教程 📚](https://dunwu.github.io/javaweb/) - 内容包含：JavaEE、分布式应用技术及原理等。

## 框架

### Spring

> [Spring 教程 📚](https://dunwu.github.io/spring-tutorial/) - Spring 各种实战。

### Spring Boot

> [Spring Boot 教程 📚](https://dunwu.github.io/spring-boot-tutorial/) - Spring Boot 各种实战。

## 工具

### Git

[Git 从入门到精通](https://github.com/dunwu/blog/blob/master/source/_posts/tools/git.md) - Git 的特性、原理、配置、命令、最佳实践、常见问题。学习 Git，基本上这篇文章就够了。

### 正则

[正则教程](https://github.com/dunwu/blog/blob/master/source/_posts/tools/regex.md) - 正则语义很晦涩，但是一旦掌握，编程绝对是一件神兵利器。

### UML

[UML 教程](https://github.com/dunwu/blog/blob/master/source/_posts/tools/uml.md) - 全面介绍 UML 各种图：类图、对象图、包图、组件图、部署图、复合结构图、活动图、状态图、用例图、通信图、交互概述图、时序图、时间图

### Gitbook

[使用 Gitbook 打造你的电子书](https://dunwu.gitbooks.io/gitbook-notes/)

## 资源

TODO
