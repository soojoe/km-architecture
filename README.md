# km-architecture
<h1 align="center">知识学习体系</h1>

## 说明

   该知识学习体系主要是本人两个月的回顾学习记录，重点是从实际项目经验的出发，总结知识的使用场景、使用注意点以及知识原理等。

## 目录

* [01-基础知识](#)
  * [01-基础](#)
  * [02-集合框架](#)
  * [03-多线程](#)
  * [04-IO](#)
  * [05-JVM](#)
  * [06-设计模式](#)
  * [07-网络](#)
  * [08-jdk新特性](#)
* [02-数据结构与算法](#)
  * [01-数据结构](#)
  * [02-算法](#)
* [03-常用框架源码解析](#)
  * [01-dubbo](*)
  * [02-Spring](#)
  * [03-ZooKeeper](#)
* [04-数据存储及缓存](#)
  * [01-MySQL](#)
  * [02-缓存](#)
  * [03-分布式存储](#)
* [05-项目实践架构经验](#)
  * [01-性能](#)
  * [02-可用性](#)
  * [03-可扩展性](#)
  * [04-可伸缩性](#)
  * [05-安全性](#)
  * [06-一致性](#)
* [06-区块链对Java传统应用的借鉴](#)
  * [01-utxo模型的应用](#)
  * [02-bloomfilter设计应用](#)
  * [03-mpt树设计应用](#)
  * [04-密码学的应用](#) 
  * [05-链式账本的应用](#) 

## ToDoList(待办清单)

* [x] 待办
* [ ] 待办
* [ ] 待办
* [x] 待办 
* [ ] 待办
* [ ] 待办
  
## Java

### 基础

* [Java 基础知识回顾](https://github.com/Snailclimb/Java-Guide/blob/master/Java/Java基础知识.md)
* [J2EE 基础知识回顾](https://github.com/Snailclimb/Java-Guide/blob/master/Java/J2EE基础知识.md)
* [Java常见关键字总结：static、final、this、super](https://github.com/Snailclimb/Java-Guide/blob/master/Java/final、static、this、super.md) 

### 集合框架

* **常见问题总结：**
  * [这几道Java集合框架面试题几乎必问](https://github.com/Snailclimb/Java-Guide/blob/master/Java/这几道Java集合框架面试题几乎必问.md)
  * [Java 集合框架常见面试题总结](https://github.com/Snailclimb/Java-Guide/blob/master/Java/Java集合框架常见面试题总结.md)
* **源码分析：**
  * [ArrayList 源码学习](https://github.com/Snailclimb/Java-Guide/blob/master/Java/ArrayList.md) 
  * [【面试必备】透过源码角度一步一步带你分析 ArrayList 扩容机制](https://github.com/Snailclimb/JavaGuide/blob/master/Java/ArrayList-Grow.md)    
  * [LinkedList 源码学习](https://github.com/Snailclimb/Java-Guide/blob/master/Java/LinkedList.md)   
  * [HashMap(JDK1.8)源码学习](https://github.com/Snailclimb/Java-Guide/blob/master/Java/HashMap.md)  

### 多线程

* [并发编程面试必备：synchronized 关键字使用、底层原理、JDK1.6 之后的底层优化以及 和ReenTrantLock 的对比](https://github.com/Snailclimb/Java_Guide/blob/master/Java/synchronized.md)
* [并发编程面试必备：乐观锁与悲观锁](https://github.com/Snailclimb/Java-Guide/blob/master/EssentialContentForInterview/面试必备之乐观锁与悲观锁.md)
* [并发编程面试必备：JUC 中的 Atomic 原子类总结](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Multithread/Atomic.md)
* [并发编程面试必备：AQS 原理以及 AQS 同步组件总结](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Multithread/AQS.md)
* [BATJ都爱问的多线程面试题](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Multithread/BATJ都爱问的多线程面试题.md)
* [并发容器总结](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Multithread/并发容器总结.md)

### JVM

* [可能是把Java内存区域讲的最清楚的一篇文章](https://github.com/Snailclimb/Java_Guide/blob/master/Java/可能是把Java内存区域讲的最清楚的一篇文章.md)
* [搞定JVM垃圾回收就是这么简单](https://github.com/Snailclimb/Java_Guide/blob/master/Java/搞定JVM垃圾回收就是这么简单.md)
* [《深入理解Java虚拟机》第2版学习笔记](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Java虚拟机（jvm）.md)

### BIO,NIO,AIO

* [BIO,NIO,AIO 总结 ](https://github.com/Snailclimb/JavaGuide/blob/master/Java/BIO%2CNIO%2CAIO%20summary.md)
* [Java IO 与 NIO系列文章](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Java%20IO与NIO.md)

### Java8 New Features

* [Java 8 新特性总结](https://github.com/Snailclimb/JavaGuide/blob/master/Java/What's%20New%20in%20JDK8/Java8Tutorial.md)

### 设计模式

* [设计模式系列文章](https://github.com/Snailclimb/Java_Guide/blob/master/Java/设计模式.md)

## 数据结构与算法

### 数据结构

* [数据结构知识学习与面试](https://github.com/Snailclimb/Java_Guide/blob/master/数据结构与算法/数据结构.md)

### 算法

* [算法学习与面试](https://github.com/Snailclimb/Java_Guide/blob/master/数据结构与算法/算法.md)  
* [常见安全算法（MD5、SHA1、Base64等等）总结](https://github.com/Snailclimb/Java_Guide/blob/master/数据结构与算法/常见安全算法（MD5、SHA1、Base64等等）总结.md)
* [算法总结——几道常见的子符串算法题 ](https://github.com/Snailclimb/Java_Guide/blob/master/数据结构与算法/搞定BAT面试——几道常见的子符串算法题.md)
* [算法总结——几道常见的链表算法题 ](https://github.com/Snailclimb/Java_Guide/blob/master/数据结构与算法/Leetcode-LinkList1.md)   

## 计算机网络与数据通信

### 网络相关

* [计算机网络常见面试题](https://github.com/Snailclimb/Java_Guide/blob/master/计算机网络与数据通信/计算机网络.md)
* [计算机网络基础知识总结](https://github.com/Snailclimb/Java_Guide/blob/master/计算机网络与数据通信/干货：计算机网络知识总结.md)
* [HTTPS中的TLS](https://github.com/Snailclimb/Java_Guide/blob/master/计算机网络与数据通信/HTTPS中的TLS.md)

### 数据通信(RESTful,RPC,消息队列)总结

* [数据通信(RESTful、RPC、消息队列)相关知识点总结](https://github.com/Snailclimb/Java-Guide/blob/master/计算机网络与数据通信/数据通信(RESTful、RPC、消息队列).md)
* [Dubbo 总结：关于 Dubbo 的重要知识点](https://github.com/Snailclimb/Java-Guide/blob/master/计算机网络与数据通信/dubbo.md)
* [消息队列总结：新手也能看懂，消息队列其实很简单](https://github.com/Snailclimb/Java-Guide/blob/master/计算机网络与数据通信/message-queue.md)
* [一文搞懂 RabbitMQ 的重要概念以及安装](https://github.com/Snailclimb/Java-Guide/blob/master/计算机网络与数据通信/rabbitmq.md)

## 操作系统

### Linux相关

* [后端程序员必备的 Linux 基础知识](https://github.com/Snailclimb/Java-Guide/blob/master/操作系统/后端程序员必备的Linux基础知识.md)  
* [Shell 编程入门](https://github.com/Snailclimb/Java-Guide/blob/master/操作系统/Shell.md)  

## 主流框架

### Spring

* [Spring 学习与面试](https://github.com/Snailclimb/Java_Guide/blob/master/主流框架/Spring学习与面试.md)
* [Spring中bean的作用域与生命周期](https://github.com/Snailclimb/Java_Guide/blob/master/主流框架/SpringBean.md)
* [SpringMVC 工作原理详解](https://github.com/Snailclimb/JavaGuide/blob/master/主流框架/SpringMVC%20%E5%B7%A5%E4%BD%9C%E5%8E%9F%E7%90%86%E8%AF%A6%E8%A7%A3.md)

### ZooKeeper

* [可能是把 ZooKeeper 概念讲的最清楚的一篇文章](https://github.com/Snailclimb/Java_Guide/blob/master/主流框架/ZooKeeper.md)
* [ZooKeeper 数据模型和常见命令了解一下，速度收藏！](https://github.com/Snailclimb/Java_Guide/blob/master/主流框架/ZooKeeper数据模型和常见命令.md)
  
## 数据存储

### MySQL

* [MySQL 学习与面试](https://github.com/Snailclimb/Java_Guide/blob/master/数据存储/MySQL.md)
* [【思维导图-索引篇】搞定数据库索引就是这么简单](https://github.com/Snailclimb/Java_Guide/blob/master/数据存储/MySQL%20Index.md)

### Redis

* [Redis 总结](https://github.com/Snailclimb/Java_Guide/blob/master/数据存储/Redis/Redis.md)
* [Redlock分布式锁](https://github.com/Snailclimb/Java_Guide/blob/master/数据存储/Redis/Redlock分布式锁.md)
* [如何做可靠的分布式锁，Redlock真的可行么](https://github.com/Snailclimb/Java_Guide/blob/master/数据存储/Redis/如何做可靠的分布式锁，Redlock真的可行么.md)

## 架构

* [一文读懂分布式应该学什么](https://github.com/Snailclimb/Java_Guide/blob/master/架构/分布式.md)
* [8 张图读懂大型网站技术架构](https://github.com/Snailclimb/JavaGuide/blob/master/架构/8%20张图读懂大型网站技术架构.md)
* [【面试精选】关于大型网站系统架构你不得不懂的10个问题](https://github.com/Snailclimb/JavaGuide/blob/master/架构/【面试精选】关于大型网站系统架构你不得不懂的10个问题.md)
