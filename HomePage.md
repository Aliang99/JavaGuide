## 目录

- [Java](#java)
    - [基础](#基础)
    - [容器](#容器)
    - [并发](#并发)
    - [JVM](#jvm)
    - [I/O](#io)
    - [Java 8](#java-8)
    - [编程规范](#编程规范)
- [网络](#网络)
- [操作系统](#操作系统)
    - [Linux相关](#linux相关)
- [数据结构与算法](#数据结构与算法)
    - [数据结构](#数据结构)
    - [算法](#算法)
- [数据库](#数据库)
    - [MySQL](#mysql)
    - [Redis](#redis)
- [系统设计](#系统设计)
    - [设计模式(工厂模式、单例模式 ... )](#设计模式)
    - [常用框架(Spring、Zookeeper ... )](#常用框架)
    - [数据通信(消息队列、Dubbo ... )](#数据通信)
    - [网站架构](#网站架构)
- [面试指南](#面试指南)
    - [备战面试](#备战面试)
    - [常见面试题总结](#常见面试题总结)
    - [面经](#面经)
- [工具](#工具)
    - [Git](#git)
    - [Docker](#Docker)
- [资料](#资料)
    - [书单](#书单)
    - [Github榜单](#Github榜单)
- [待办](#待办)
- [说明](#说明)

## Java

### 基础

* [Java 基础知识回顾](java/Java基础知识.md)
* [Java 基础知识疑难点总结](java/Java疑难点.md)
* [J2EE 基础知识回顾](java/J2EE基础知识.md)

### 容器

* [Java容器常见面试题/知识点总结](java/collection/Java集合框架常见面试题.md)
* [ArrayList 源码学习](java/collection/ArrayList.md)  
* [LinkedList 源码学习](java/collection/LinkedList.md)   
* [HashMap(JDK1.8)源码学习](java/collection/HashMap.md)  

### 并发

* [Java 并发基础常见面试题总结](java/Multithread/JavaConcurrencyBasicsCommonInterviewQuestionsSummary.md)
* [Java 并发进阶常见面试题总结](java/Multithread/JavaConcurrencyAdvancedCommonInterviewQuestions.md)
* [并发容器总结](java/Multithread/并发容器总结.md)
* [乐观锁与悲观锁](essential-content-for-interview/面试必备之乐观锁与悲观锁.md)
* [JUC 中的 Atomic 原子类总结](java/Multithread/Atomic.md)
* [AQS 原理以及 AQS 同步组件总结](java/Multithread/AQS.md)

### JVM
* [一 Java内存区域](java/jvm/Java内存区域.md)
* [二 JVM垃圾回收](java/jvm/JVM垃圾回收.md)
* [三 JDK 监控和故障处理工具](java/jvm/JDK监控和故障处理工具总结.md)
* [四 类文件结构](java/jvm/类文件结构.md)
* [五 类加载过程](java/jvm/类加载过程.md)
* [六 类加载器](java/jvm/类加载器.md)

### I/O

* [BIO,NIO,AIO 总结 ](java/BIO-NIO-AIO.md)
* [Java IO 与 NIO系列文章](java/Java%20IO与NIO.md)

### Java 8 

* [Java 8 新特性总结](java/What's%20New%20in%20JDK8/Java8Tutorial.md)
* [Java 8 学习资源推荐](java/What's%20New%20in%20JDK8/Java8教程推荐.md)

### 编程规范

- [Java 编程规范](java/Java编程规范.md)

## 网络

* [计算机网络常见面试题](network/计算机网络.md)
* [计算机网络基础知识总结](network/干货：计算机网络知识总结.md)
* [HTTPS中的TLS](network/HTTPS中的TLS.md)

## 操作系统

### Linux相关

* [后端程序员必备的 Linux 基础知识](operating-system/后端程序员必备的Linux基础知识.md)  
* [Shell 编程入门](operating-system/Shell.md) 

## 数据结构与算法

### 数据结构

- [数据结构知识学习与面试](dataStructures-algorithms/数据结构.md)

### 算法

- [算法学习资源推荐](dataStructures-algorithms/算法学习资源推荐.md)  
- [几道常见的字符串算法题总结 ](dataStructures-algorithms/几道常见的子符串算法题.md)
- [几道常见的链表算法题总结 ](dataStructures-algorithms/几道常见的链表算法题.md)   
- [剑指offer部分编程题](dataStructures-algorithms/剑指offer部分编程题.md)
- [公司真题](dataStructures-algorithms/公司真题.md)
- [回溯算法经典案例之N皇后问题](dataStructures-algorithms/Backtracking-NQueens.md)

## 数据库

### MySQL

* [MySQL 学习与面试](database/MySQL.md)
* [一千行MySQL学习笔记](database/一千行MySQL命令.md)
* [MySQL高性能优化规范建议](database/MySQL高性能优化规范建议.md)
* [数据库索引总结](database/MySQL%20Index.md)
* [事务隔离级别(图文详解)](database/事务隔离级别(图文详解).md)
* [一条SQL语句在MySQL中如何执行的](database/一条sql语句在mysql中如何执行的.md)

### Redis

* [Redis 总结](database/Redis/Redis.md)
* [Redlock分布式锁](database/Redis/Redlock分布式锁.md)
* [如何做可靠的分布式锁，Redlock真的可行么](database/Redis/如何做可靠的分布式锁，Redlock真的可行么.md)

## 系统设计

### 设计模式

- [设计模式系列文章](system-design/设计模式.md)

### 常用框架

#### Spring

- [Spring 学习与面试](system-design/framework/spring/Spring.md)
- [Spring 常见问题总结](system-design/framework/spring/SpringInterviewQuestions.md)
- [Spring中bean的作用域与生命周期](system-design/framework/spring/SpringBean.md)
- [SpringMVC 工作原理详解](system-design/framework/spring/SpringMVC-Principle.md)
- [Spring中都用到了那些设计模式?](system-design/framework/spring/Spring-Design-Patterns.md)

#### ZooKeeper

- [ZooKeeper 相关概念总结](system-design/framework/ZooKeeper.md)
- [ZooKeeper 数据模型和常见命令](system-design/framework/ZooKeeper数据模型和常见命令.md)

### 数据通信

- [数据通信(RESTful、RPC、消息队列)相关知识点总结](system-design/data-communication/summary.md)
- [Dubbo 总结：关于 Dubbo 的重要知识点](system-design/data-communication/dubbo.md)
- [消息队列总结](system-design/data-communication/message-queue.md)
- [RabbitMQ 入门](system-design/data-communication/rabbitmq.md)
- [RocketMQ的几个简单问题与答案](system-design/data-communication/RocketMQ-Questions.md)

### 网站架构

- [一文读懂分布式应该学什么](system-design/website-architecture/分布式.md)
- [8 张图读懂大型网站技术架构](system-design/website-architecture/8%20张图读懂大型网站技术架构.md)
- [【面试精选】关于大型网站系统架构你不得不懂的10个问题](system-design/website-architecture/【面试精选】关于大型网站系统架构你不得不懂的10个问题.md)

## 面试指南

### 备战面试

* [【备战面试1】程序员的简历就该这样写](essential-content-for-interview/PreparingForInterview/程序员的简历之道.md)
* [【备战面试2】初出茅庐的程序员该如何准备面试？](essential-content-for-interview/PreparingForInterview/interviewPrepare.md)
* [【备战面试3】7个大部分程序员在面试前很关心的问题](essential-content-for-interview/PreparingForInterview/JavaProgrammerNeedKnow.md)
* [【备战面试4】Github上开源的Java面试/学习相关的仓库推荐](essential-content-for-interview/PreparingForInterview/JavaInterviewLibrary.md)
* [【备战面试5】如果面试官问你“你有什么问题问我吗？”时，你该如何回答](essential-content-for-interview/PreparingForInterview/如果面试官问你“你有什么问题问我吗？”时，你该如何回答.md)
* [【备战面试6】美团面试常见问题总结（附详解答案）](essential-content-for-interview/PreparingForInterview/美团面试常见问题总结.md)

### 常见面试题总结

* [第一周（2018-8-7）](essential-content-for-interview/MostCommonJavaInterviewQuestions/第一周（2018-8-7）.md) (为什么 Java 中只有值传递、==与equals、 hashCode与equals)
* [第二周（2018-8-13）](essential-content-for-interview/MostCommonJavaInterviewQuestions/第二周(2018-8-13).md)(String和StringBuffer、StringBuilder的区别是什么？String为什么是不可变的？、什么是反射机制？反射机制的应用场景有哪些？......)
* [第三周（2018-08-22）](java/collection/Java集合框架常见面试题.md) （Arraylist 与 LinkedList 异同、ArrayList 与 Vector 区别、HashMap的底层实现、HashMap 和 Hashtable 的区别、HashMap 的长度为什么是2的幂次方、HashSet 和 HashMap 区别、ConcurrentHashMap 和 Hashtable 的区别、ConcurrentHashMap线程安全的具体实现方式/底层具体实现、集合框架底层数据结构总结）
* [第四周(2018-8-30).md](essential-content-for-interview/MostCommonJavaInterviewQuestions/第四周(2018-8-30).md) （主要内容是几道面试常问的多线程基础题。）

### 面经

- [5面阿里,终获offer(2018年秋招)](essential-content-for-interview/BATJrealInterviewExperience/5面阿里,终获offer.md)
- [蚂蚁金服2019实习生面经总结(已拿口头offer)](essential-content-for-interview/BATJrealInterviewExperience/蚂蚁金服实习生面经总结(已拿口头offer).md)
- [2019年蚂蚁金服、头条、拼多多的面试总结](essential-content-for-interview/BATJrealInterviewExperience/2019alipay-pinduoduo-toutiao.md)

## 工具

### Git

* [Git入门](tools/Git.md)

### Docker

* [Docker 入门](tools/Docker.md)
* [一文搞懂 Docker 镜像的常用操作！](tools/Docker-Image.md)

## 资料

### 书单

- [Java程序员必备书单](data/java-recommended-books.md)

### Github榜单

- [Java 项目月榜单](github-trending/JavaGithubTrending.md)

***

## 待办

- [x] [Java 8 新特性总结](./java/What's%20New%20in%20JDK8/Java8Tutorial.md)
- [x] [Java 8 新特性详解](./java/What's%20New%20in%20JDK8/Java8教程推荐.md)
- [ ] Java 多线程类别知识重构(---正在进行中---)
- [x] [BIO,NIO,AIO 总结 ](./java/BIO-NIO-AIO.md)
- [ ] Netty 总结(---正在进行中---)
- [ ] 数据结构总结重构(---正在进行中---)
