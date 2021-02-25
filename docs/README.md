
## 计算机基础
### **概述**
- [计算机基础](计算机基础/计算机基础)
---

##  Java

---

> [!NOTE]
>
> Java 是由 Sun Microsystems 公司于 1995 年 5 月推出的 Java 面向对象程序设计语言和 Java 平台的总称。由 James Gosling和同事们共同研发，并在 1995 年正式推出。后来 Sun 公司被 Oracle （甲骨文）公司收购，Java 也随之成为 Oracle 公司的产品。

### Java 基础

- [Java 小白成长记 · 第 1 篇「万物皆对象」](java/javaweb第一天笔记)

### Java 单词

- [Java 编程语言单词汇总](java/Java 编程语言单词汇总)

### 设计模式

> [!NOTE]
> 设计模式是**解决问题的方案**，学习现有的设计模式可以做到经验复用。拥有设计模式词汇，在沟通时就能用更少的词汇来讨论，并且不需要了解底层细节。

- 设计模式七大原则
- 二十三种设计模式 <span data-v-73ca276e="" class="badge warning" style="vertical-align: base-line;">Vital</span>

## 必备框架

---

> [!WARNING|label:注意区分下数据库和 ORM 框架！]
> 
>**数据库**：存储数据。常见的数据库如：
> 
>- MySQL
> - Oracle
> 
>**ORM 框架**：`Object Relational Mapping` 对象关系映射，将实体类对象持久化到数据库中。可以简单的认为 ORM 框架就是用来操作数据库的。常见的 ORM 框架如：
> 
>- JDBC
> - MyBatis （常见组合为 <u>Spring + SpringMVC</u> / Spring Boot + MyBatis + 数据库）
> - Hibernate（常见组合为 Spring Boot + Hibernate + Spring Data JPA + 数据库）

### SSM

- 1 - **Spring (Framework)**
  - 1.1 - Spring 简介 + Spring IoC 详解 <span data-v-73ca276e="" class="badge warning" style="vertical-align: base-line;">Vital</span>
  - 1.2 - Spring IoC 容器源码分析
  - 1.3 - Spring AOP 详解Vital
  - 1.4 - Spring AOP 源码分析
  - 1.4 - Spring 事务控制
  - <u> Spring 面试指南</u>
- 2 - **SpringMVC**
  - Spring MVC 知识点全解
  - <u> SpringMVC 面试指南</u>
- 3 - **MyBatis**
  - MyBatis 知识点全解
  - 使用 PageHelper 前先学会手写一个分页查询吧（SpringBoot 版）
  - <u> MyBatis 面试指南</u>
- 4 - SSM 框架整合实例

### Spring Boot 2.x

1 - Spring Boot 入门

2 - 配置文件

3 - 自定义 starter

4 - 日志

5 - Web 开发

7 - Web 开发 - 实战案例

6 - SpringBoot 前后端数据交互的几种常用方式 ⭐ 

8 - SpringBoot 与数据访问

9 - **Spring Data JPA**

- 🛫 Spring Boot + Spring Data JPA 一篇文章快速入门
- 9.1 - 实体类映射到数据库表的基本注解
- 9.2 - 表之间的映射关系
- 9.3 - Spring Data JPA 的四种查询方式
- 9.4 - Spring Data JPA 的更新方式详解

10 - 异步、定时、邮件任务

11 - 集成 Redis（Lettuce）

<u> SpringBoot 面试指南</u>

[开源社区系统 — Echo](https://github.com/Veal98/Echo)：基于 SpringBoot + MyBatis + MySQL + Redis + Kafka + Elasticsearch + Spring Security + ... 并提供详细的开发文档和配套教程 <span data-v-73ca276e="" class="badge recommendation" style="vertical-align: base-line;">项目经验首选</span>

### Netty 4.x

> [!Note]
> Netty 是目前 **Java 网络编程**最热门的框架，很多开源项目涉及到**网络通信**的部分都是基于 Netty 来做的，比如 Dubbo、RocketMQ、ElasticSearch 等。**学习 Netty 前请务必掌握 Java I/O 的相关知识**。并请注意 **Netty 5 已被官方废弃**，本笔记基于 Netty 4.x

- 1 - 从 BIO、NIO 到 Netty
- 2 - 第一个 Netty 应用：HelloWorld
- 3 - Netty 架构设计与特性
- 4 - Netty 核心组件总览
- 5 - Transport（传输）详解
- 6 - Buffer（缓冲/字节容器）详解
- 7 - ChannelHandler（消息处理器）与 ChannelPipeline 详解
- 8 - Netty Reactor 线程模型与 EventLoop（事件循环）详解 <span data-v-73ca276e="" class="badge warning" style="vertical-align: base-line;">Vital</span>
- 9 - Bootstrap（引导）详解
- 10 - Codec（编码与解码）详解
- 11 - 实例及分析：Netty 实现聊天功能
- 12 - Netty 是如何解决 TCP 粘包/拆包问题的
- 13 - Netty 是如何实现 TCP 心跳机制与断线重连的
- 14 - 实例及分析：Netty + Kryo 序列化传输对象
- <u> Netty 面试指南</u>

##  mysql

---

### 学成在线

> MySQL 是最流行的关系型数据库管理系统，在 WEB 应用方面 MySQL 是最好的 RDBMS(Relational Database Management System：关系数据库管理系统)应用软件之一。

[MYSQL基础](mysql/MYSQL基础)

##  工具

---

### Git

### Docker

## 图书管理系统

---

### 图书管理系统

- [图书管理系统](图书管理系统/图书管理系统)

### 图书管理系统需求调研提纲

- [图书管理系统需求调研提纲](图书管理系统/图书管理系统需求调研提纲)

### 图书管理系统软件开发模型确认

- [图书管理系统软件开发模型确认](图书管理系统/图书管理系统软件开发模型确认)

##  hexo

---

### Hexo博客使用gulp压缩静态资源进行优化

Gulp.js 是一个自动化构建工具，开发者可以使用它在项目开发过程中自动执行常见任务。Gulp.js 是基于 Node.js 构建的，利用 Node.js 流的威力，你可以快速构建项目并减少频繁的 IO 操作。Gulp.js 源文件和你用来定义任务的 Gulp 文件都是通过 JavaScript（或者 CoffeeScript ）源码来实现的。

  - [Hexo博客使用gulp压缩静态资源进行优化](hexo/Hexo博客使用gulp压缩静态资源进行优化)

### Hexo-xr

  - [Hexo-xr](hexo/Hexo-xr)

##  网页源码

---

### 品优购

> [!TIP]
> 品优购网上商城是一个综合性的 B2B2C 平台，类似京东商城、天猫商城。网站采用商家入驻的模式，商家入驻平台提交申请，有平台进行资质审核，审核通过后，商家拥有独立的管理后台录入商品信息。商品经过平台审核后即可发布。以下是静态源码及展示页面。

  - [品优购](网页源码/品优购)
  - [品优购进阶版](网页源码/品优购进阶版)

---

### 学成在线

> 学成在线借鉴了MOOC(大型开放式网络课程，即MOOC(massive open online courses))的设计思想，是一 个提供IT职业课程在线学习的平台，它为即将和已经加入IT领域的技术人才提供在线学习服务，用户通过在线学 习、在线练习、在线考试等学习内容，最终掌握所学的IT技能，并能在工作中熟练应用。

- [学成在线](网页源码/学成在线)

### 仿哔哩哔哩

> bilibili是国内知名的视频弹幕网站，这里有及时的动漫新番，活跃的ACG氛围，有创意的Up主。大家可以在这里找到许多欢乐。以下是B站主页静态代码下载地址及页面展示。

- [仿哔哩哔哩](网页源码/仿哔哩哔哩)

### 仿哔哩哔哩

- [吃热狗程序开发](网页源码/吃热狗程序开发)

## 博客笔记汇总

[博客笔记汇总](博客/博客笔记汇总)

## 落雪音乐助手

> 落雪音乐助手是一款非常实用的免费音乐下载软件，是基于 Electron + Vue 开发的音乐软件，支持win、Mac和Linux平台，整合了市场上主流音乐软件的搜索接口，聚合各音乐平台，完善软件设计！

- [落雪音乐助手](落雪/落雪音乐助手)

##  其他

---

## 公众号

一个正在追梦的少年。关注我，陪有梦想的你一起成长。

![](https://gitee.com/kuiler/imgaes/raw/master/img/640.webp)







