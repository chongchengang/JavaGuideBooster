# JavaGuide
<a href="#1">Java应届生面试突击</a> <br>
<a href="#2">Java工程师面试突击</a>

### <a name="1">Java应届生面试突击</a>

---
#### Java基础
&ensp;&ensp; ♦ JVM相关 <br>
&ensp;&ensp;&ensp;&ensp; • [说一下Java的垃圾回收机制]() <br>
&ensp;&ensp;&ensp;&ensp; • [JVM的内存布局内存模型]() <br>
&ensp;&ensp;&ensp;&ensp; • [JVM的4种引用和使用场景]() <br>


#### 多线程和并发
&ensp;&ensp; • [什么是缓存一致性问题,如何解决呢]()

#### 数据库
&ensp;&ensp; • [进程间的通信方式,进程调度方法]()

#### 操作系统
&ensp;&ensp; • [优化查询的方法]()

#### 计算机网络
&ensp;&ensp; ♦ TCP/IP相关的问题 <br>
&ensp;&ensp;&ensp;&ensp; • [OSI与TCP IP各层的结构与功能,都有哪些协议,协 所占端口号]()

### <a name="2">Java工程师面试突击</a>

--- 
#### 消息中间件
- [如何进行消息队列的选型]()
- [引入消息队列后如何保证其可用性]()
- [为什么消息队列里消费到了重复数据]()
- [发到消息队列的数据不见了]()
- [如何保证从消息队列拿到的数据按照顺序执行]()
- [几百万消息在小消息队列里积压了几小时]()
- [如果让你开发一个消息中间件,你会怎么设计架构]()
- [消息队列相关问题的面试技巧]()

#### 分布式搜索
- [分布式引擎架构是怎么设计的,为什么是分布式的]()
- [分布式搜索引擎写入和查询的工作流程]()
- [分布式搜索引擎在几十亿数据量级的场景下如何优化查询性能]()
- [04_你们公司分布式搜索引擎是怎么部署的]()
- [分布式搜索引擎相关问题的面试技巧]()

#### 分布式缓存
- [分布式缓存第一个问题]()
- [redis线程模型,为什么单线程还是有很高的效率]()
- [redis有哪些数据类型,分别在什么场景下使用比较合适]()
- [redis过期策略,手写LRU]()
- [怎么保证redis是高并发和高可用]()
- [怎么保证redis挂掉之后再重启数据可以恢复]()
- [redis cluster集群模式的原理]()
- [一般如何应对缓存雪崩以及穿透问题]()
- [如何保证缓存与数据库双写时的数据一致性]()
- [redis的并发竞争该如何解决]()
- [你们公司生产环境的redis集群的部署架构是什么样的]()
- [分布式缓存面试题的回答技巧]()

#### 分布式系统
- [为什么要把系统拆分为分布式,为啥要用dubbo]()
- [dubbo的工作原理,注册中心挂了可以继续通信嘛]()
- [dubbo都支持哪写通信协议以及序列化协议]()
- [dubbo支持哪写负载均衡,高可用以及动态代理策略]()
- [SPI是啥意思,dubbo的SPI机制原理]()
- [基于dubbo如何做服务治理、服务降级以及重试]()
- [分布式接口的幂等性如何保证,比如不能重复扣款]()
- [分布式系统中的接口调用如何保证顺序性]()
- [如何设计一个类似dubbo的rpc框架,架构上如何考虑]()
- [zookeeper一般都有哪写使用场景]()
- [什么是分布式锁,对比redis和zk两种分布式锁的优劣]()
- [说说你们的分布式session方案,怎么做的]()
- [分布式事务方案,有啥坑]()
- [一般如何设计一个高并发的系统架构]()

#### 数据库
- [如何分库分表]()
- [如何系统不停机迁移到分库分表]()
- [如何设计可动态扩容缩容的分库分表方案]()
- [分库分表后全局id如何生成]()
- [MySQL读写分离的原理,主从同步如何解决]()


    