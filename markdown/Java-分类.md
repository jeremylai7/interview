### Java
* 简述 Java 的反射机制及其应用场景
* Java 类的加载流程是怎样的？什么是双亲委派机制？
* Java 中 sleep() 与 wait() 的区别
* String 类能不能被继承？为什么？
* 简述 BIO, NIO, AIO 的区别
* Java 中接口和抽象类的区别
* hashcode 和 equals 方法的联系
* String，StringBuffer，StringBuilder 之间有什么区别？ 
### 缓存
* Redis 缓存雪崩、穿透以及击穿，如何应对这些情况。
* 如何解决数据库和缓存数据不一致情况。
* redis分布式锁
* redis集群部署，（三个集群部署方式，主从、哨兵、Cluster模式）
* redis 数据结构 简单动态字符串（sds）、双链表、字典、跳表。
* 各种数据结构应用场景

### 消息队列
* 如何保证消息可靠传输
* 如何保证消息不被重复消费
* 如何保证消息的顺序性



### jdk 1.8新特定以及底层原理
* Lambda 表达式，语法糖
* 

### 设计模式
* 单例模式（七种写法）
  * 实现单例设计模式（懒汉，饿汉）
* 策略模式
* 工厂模式
* 代理模式

### 集合
* list集合
* set集合
* 简述 ArrayList 与 LinkedList 的底层实现以及常见操作的时间复杂度
* 集合的源码
  * arrayList 和 linkedList 的区别
  * arrayList 源码
  * linkedList 源码
  * hashmap 源码
    * 红黑树和平衡二叉树的区别
  * currentHashMap 源码
  * jdk1.8 hashmap 扩容新特性
  * HashMap 与 ConcurrentHashMap 的实现原理是怎样的？ConcurrentHashMap 是如何保证线程安全的？
    * ConcurrentHashMap 
      * jdk1.7 采用分段锁技术，每个Segment位于一个段   
      * jdk1.8 抛弃了Segment 分段锁，采用CAS + synchronized 保证线程安全
* Java 是如何实现线程安全的，哪些数据结构是线程安全的？
* HashMap 实现原理，为什么使用红黑树？

### 线程池
* 七个参数的含义
  * 核心线程数
  * 最大线程数
  * 阻塞队列
  * 拒接策略
* 线程池执行顺序
* 核心线程回收
* 线程池里的 arrayblockingqueue 与 linkedblockingqueue 的使用场景和区别
* 线程池是如何实现的？简述线程池的任务策略

### spring 和springboot
* springboot 自动配置
* spring 源码
* springboot 源码
* bean 的生命周期
* 简述 Spring AOP 的原理 
* Spring MVC 的原理和流程
* 简述 Spring bean 的生命周期

### jvm分区 和 gc
* jvm分区
  * 程序计数器
  * 虚拟机栈
  * 本地方法栈
  * 方法区
  * 堆
  * 线程私有的：程序计数器、虚拟机栈、本地方法栈
  * 线程共享的：堆、方法区、直接内存
* JVM 是怎么去调优的？了解哪些参数和指令？
* Java 中如何进行 GC 调优？


* Java 中垃圾回收机制中如何判断对象需要回收？常见的 GC 回收算法有哪些？
  * 程序计数法
  * 可达性分析法
* JMM 中内存模型是怎样的？什么是指令序列重排序

### 锁
  * 简述 Synchronized，Volatile，可重入锁的不同使用场景及优缺点
  * Synchronized 关键字底层是如何实现的？它与 Lock 相比优缺点分别是什么？ 
  
  

