### 缓存
* Redis 缓存雪崩、穿透以及击穿，如何应对这些情况。
* 如何解决数据库和缓存数据不一致情况。


### 消息队列

### jdk 1.8新特定以及底层原理
* Lambda 表达式，语法糖
* 

### 设计模式
* 单例模式（七种写法）
* 策略模式
* 工厂模式
* 代理模式

### 集合
* list集合
* set集合
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

### 线程池
* 七个参数的含义
  * 核心线程数
  * 最大线程数
  * 阻塞队列
  * 拒接策略
* 线程池执行顺序
* 核心线程回收
* 线程池里的 arrayblockingqueue 与 linkedblockingqueue 的使用场景和区别



