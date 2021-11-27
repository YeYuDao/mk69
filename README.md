# mk69
Java实操避坑指南
Java实操避坑指南
[![下载地址](https://img.mukewang.com/szimg/5fc066fb091b3eba05400304.jpg "下载地址")](https://51xueit.vip "下载地址")
[下载地址](https://51xueit.vip "下载地址")
### 第1章 课程介绍 

#### 介绍制作这门课程的初衷、我对这门课程的定位以及愿景，课程中包含了哪些内容，能够帮助你什么，以及怎样去学习这门课程，才能更好的消化吸收。
1-1 为什么做这门课 (05:19)

1-2 为何我们需要每一个你

1-3 感悟之外，你有困扰了还可以这样

1-4 面试经历的讨论


### 第2章 Java 空指针和异常 – 常犯指数5星 

#### 空指针问题和各种常见的异常（并发修改、类型转换）几乎是所有 Java 初学者最头疼的问题，本章将会教会你怎么避免这些问题、如何使用 Optional 规避空指针问题，以及正确的使用 try catch 捕获异常
2-1 如何从根源避免空指针 (18:59)

2-2 赋值时自动拆箱出现空指针 (17:43)

2-3 字符串、数组、集合在使用时出现空指针怎么办？ (13:27)

2-4 使用 Optional 需要注意些什么？ (18:51)

2-5 明明 try catch 了却没有解决好异常？ (20:04)

2-6 常见异常：并发修改、类型转换、枚举查找 (13:51)

2-7 编码中常见异常解决办法 (14:17)

2-8 使用 try finally 资源泄露隐患 (20:53)

2-9 高效工具的分享

2-10 学习Java语言的难点


### 第3章 Java 计算、集合、接口 – 常犯指数4星

#### 无论什么业务开发，都离不开计算和集合数据结构的使用，频繁的使用带来频繁的出错显然是不能接受的，本章会让你看到最常见的错误以及解决办法；初学者常常会混淆接口和抽象类，尤其是 Java8 增加了默认和静态方法以后，这种情况就更加严重了，本章会教你怎样正确的使用和理解它们...
3-1 BigDecimal出错？都是精度的锅 (17:21)

3-2 为啥老用不好日期计算？ (10:40)

3-3 SimpleDateFormat线程不安全的原因 (08:38)

3-4 我只想迭代元素，不需要索引呀 (11:02)

3-5 嵌套迭代，小心外面的过早耗尽！ (11:30)

3-6 如果不好好判等，集合存储就会乱套 (23:59)

3-7 使用 lombok 注解，没有达到预期该怎么办？ (21:38)

3-8 怎么避免抽象类和接口选择失误呢？ (18:21)

3-9 接口的默认方法和静态方法改写总不合预期？ (17:33)

3-10 lambda表达式不是什么地方都能写 (18:58)

3-11 lambda和Stream真的高效吗？ (19:06)

3-12 Redis 数据结构


### 第4章 泛型、反射、编译优化 – 常犯指数3星 

#### 泛型和反射都属于 Java 语言的高级特性，初学者容易引发各种异常和问题，本章带你剖析、理解并学会使用这些高级特性；虽然编译器会对我们的代码做优化，但是并不一定每次都是合理的，所以，我们不能依赖编译器的优化，本章也会带你解析这个问题...
4-1 父类没有实现Serializable，子类就不能实现了吗？ (16:06)

4-2 实现了 Serializable 接口却报错怎么办？ (15:05)

4-3 泛型不仅仅是规定集合中的类型那么简单 (11:31)

4-4 你必须要知道的泛型特性 (16:05)

4-5 使用原始类型可能会出现灾难性后果 (16:27)

4-6 反射同样也是有缺陷的 (18:08)

4-7 反射获取不到 Method 是为什么呢？ (15:30)

4-8 并不是所有的字符串拼接都使用 StringBuilder (16:58)

4-9 面试时答上来深浅拷贝，实际中会用吗？ (13:55)

4-10 你的序列化实现的是深拷贝还是浅拷贝？ (13:49)


### 第5章 Java 线程安全 – 常犯指数3星

#### 关于线程安全、多线程等等诸如此类的问题，可谓是难倒了一大批 Java 初学者，之所以会这样，是因为没有思路、没有方法去攻破这一类知识点，本章将带着你领略线程安全、多线程的魅力，让你学会正确、合理的使用它们。
5-1 用不好 Synchronized 关键字 (27:53)

5-2 多线程下怎么更新变量值才好 (16:34)

5-3 提到阻塞队列，你是不是感觉到很懵 (25:19)

5-4 并不是什么时候都适合用 Copy-On-Write (19:17)

5-5 使用线程池，你有没有遇到过拒绝执行异常？ (20:27)

5-6 线程池其实是用来管理线程的工具 (13:42)

5-7 如何实现对线程状态监控？ (14:02)

5-8 ThreadLocal不是用来解决并发或共享问题的 (13:39)

5-9 用不好 ThreadLocal，极有可能出现内存泄漏 (18:48)


### 第6章 Spring 中的坑

#### 对于初学 Spring 的同学来说，能够用好 Spring 是一件不容易的事，关于 Bean 的名称、自动注入、容器与上下文的理解、Scope、循环依赖、事务等等问题是层出不穷，本章将会带着你读懂 Spring 的特性，理解并用好 Spring
6-1 Spring配置文件要小心“一步到位” (10:47)

6-2 你知道Spring Bean 的默认名称生成策略吗？ (11:45)

6-3 使用了 @Autowired 注解，但是仍然出现了空指针 (17:04)

6-4 不使用自动注入你还会获取上下文吗？（上） (10:52)

6-5 不使用自动注入你还会获取上下文吗？（下） (14:08)

6-6 Bean 的数据不符合预期怎么办 (16:19)

6-7 你是不是经常报“存在多个可用 Bean ”异常？（上） (18:43)

6-8 你是不是经常报“存在多个可用 Bean ”异常？（下） (14:29)

6-9 Spring Bean 出现了循环依赖，该怎么办？ (17:55)

6-10 Bean实例化之前我们还能做点儿什么？ (15:06)

6-11 学会利用Bean的生命周期，事半功倍 (13:38)

6-12 你的@Transactional标对位置了吗？ (17:06)

6-13 写了@Transactional也不能回滚？ (13:30)

6-14 Spring的核心特征


### 第7章 SpringMVC 中的坑

#### 相信你一定遇到过响应码、序列化与反序列化方面的问题，且可能还分不清拦截器和过滤器有什么区别、如何去使用，以及流在读取过程中出现的方法互斥问题，本章将带着你理解这些特性，规避常见的错误用法
7-1 你是不是总看不明白别人的自定义的异常？ (12:59)

7-2 明明该抛出自定义的异常，怎么还报500？ (13:49)

7-3 时间格式不能正常转换？检查下POST请求吧 (15:57)

7-4 时间格式局部处理真的好吗？ (15:29)

7-5 调试时进不去断点？可能是多个Fliter卡住了 (15:30)

7-6 日志到底该放在拦截器，还是过滤器中 (16:46)

7-7 读取了Request输入流，请求数据就不见了 (19:03)

7-8 获取不到数据？可能是方法互斥的锅 (20:09)


### 第8章 SpringBoot 中的坑

#### SpringBoot 依赖于配置，但是你搞清楚配置优先级的问题了吗？定时任务和异步任务写起来很简单，但是出现了问题如何去排查解决呢？默认的 Jackson工具你又了解多少呢？本章将带着你正确的使用这些特性和知识点
8-1 配置总出错？是不是同时用了.properties和.yml？ (10:29)

8-2 换个位置配置就失效？搞清楚加载顺序吧 (13:00)

8-3 定时任务不定时了，这到底是怎么了？ (15:51)

8-4 线程池出错缺看不出原因？可能是异步任务没处理好 (16:15)

8-5 异步任务超时怎么办？ (16:37)

8-6 速度慢，有没有想过可能是ObjectMapper实例化太多次？ (17:38)

8-7 Jackson和fastJson到底有啥区别？ (17:25)


### 第9章 MySQL 中的坑

#### 初学者一定要能够理解并正确的使用数据类型、索引和事务，这是数据库最基本的特性，之后逐步进阶到慢查询优化、学会分库分表等等，本章跟着我一起学习、理解这些知识点吧
9-1 表属性设置为 NULL，你可能要面临很多麻烦 (22:06)

9-2 不再随意设置数据类型，不给未来留隐患 (26:12)

9-3 索引加的不好，效果可能适得其反（上） (14:46)

9-4 索引加的不好，效果可能适得其反（下） (13:44)

9-5 MySQL 为什么莫名其妙的断开连接 (17:51)

9-6 事务处理出错？可能是锁用的不对 (25:55)

9-7 你写的 SQL 可能很慢，怎样做优化呢？ (24:28)

9-8 数据量逐渐增大，才考虑分库分表可行吗？ (22:19)


### 第10章 Redis 中的坑

#### 键值对类型的缓存看起来非常简单，但是，如何选择合适的数据结构并不是一件简单的事；在使用的过程中，还要考虑性能、内存优化、数据持久化、缓存的穿透和雪崩等等问题，这听起来就更加不容易了。不过，本章将会带着你逐个理解、攻破这些问题和知识点...
10-1 怎么正确的选择数据类型，让维护不再是噩梦 (14:23)

10-2 使用了事务功能，怎么没回滚呢？ (16:09)

10-3 Redis 性能上不去，可能是有 big key (14:20)

10-4 Redis 怎么出现了内存耗尽 (15:29)

10-5 有了过期机制以后内存还不够用怎么办？ (11:11)

10-6 如何解决频繁的命令往返造成的性能瓶颈？ (23:01)

10-7 你配置好持久化机制了吗？ (21:55)

10-8 你的代码是不是有缓存穿透隐患？ (10:38)

10-9 出现缓存雪崩该怎么办？如何避免？ (08:58)


[下载地址](https://51xueit.vip "下载地址")
