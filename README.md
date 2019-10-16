1)根据简历,哪个项目印象最深刻?

无分值,但是根据简历,确定后续的问题主要覆盖面。

2)这个项目架构设计是怎么样的?有哪些系统,哪些部署环境,整个的功能和数据流向是怎么样的?

能够完整地说出系统的功能,部署的环境,数据的流向。评定相应的分值:1-5

3)这个项目用了哪些技术?为什么要用这些技术?

清晰地说出所使用的技术、框架,知道这些技术的使用目的。评定相应的分值:1-5

4)实施时发现这些技术有哪些优缺点?优点是怎样发挥利用的,缺点是如何克服的?

很明确这些技术本身的优缺点,清楚描述优点的发挥场景,以及对缺点的克服、绕过方案。评定相应的分值:1-5

5) 最后项目完成后,觉得当初的设计有哪些问题,应该做哪些改进?

有没有反思架构的设计,有没有想过某些技术的合理性并考虑重新选择,并分析改进和

替换的原因。



描述一个系统，功能，设计，实现 描述

团队结构，工作职责 描述

为什么采用一个技术，为什么不使用一个技术 描述

应用中有使用到集群么？多大规模？ cluster

"cluster中应用中碰到的问题,session共享问题？" cluster

如何实现集群?session复制？无状态？集中session？ cluster

Collections和Collection的区别? collection

HashMap和HashTable的区别 collection

Java中有那些集合的接口 collection

Map与Collection的关系? collection

ClassLoader是如何查找类的？ core

equals与==的区别 core

"Exception,checked,unchecked" core

exception机制，层次 core

final关键词的使用 core

hashCode()方法的作用 core

InputStream与Reader的区别 core

interface与abstract类的区别 core

Java非阻塞I/O？ core

Java的基本对象Object有哪些方法? core

"Java中反射的性能如何,你是怎么看待的" core

Object的hashCode()的计算，肯定唯一的吗？ core

典型的web应用的classloader结构 core

"对象要实现排序,需要实现什么接口" core

请问你在什么情况下会在你的JAVA代码中使用可序列化？ core

如何保证一个类的非静态方法在多个实例中是同步的？ core

如何将一个String转化为int core

如何序列化一个类的实例 core

怎么样克隆一个类 core

怎样标识JavaBean对象里面的一个属性不需要被序列化？ core

Java中内存调优的参数 gc

垃圾收集是什么，为什么需要，怎么工作 gc

ajax http

cookie&session http

cookie的原理 http

http中的forward和redirect的区别 http

ear应用中classloader的结构 jee

EJB有哪几种事务属性(TransactionPropagationAttributes)？请阐述它们之间的区别。 jee

JMS的有哪几种消息模型？ jee

statefulsessionbean的生命周期 jee

请详细描述StatefulSessionBean的生命周期。 jee

"在一个EJB容器中,容器如何知道事务已经完成并且可以提交了？用户如何控制事务回滚？" jee

AOP的含义与用途 opensource

Ioc的含义与用途 opensource

Spring用过那些功能 opensource

Structs中处理请求的流程 opensource

解释springaop，transaction，FactoryBean&BeanFactory opensource

你知道IoC(InversionofControl)吗？IoC有哪几种类型？使用IoC有哪些好处？现在有哪些比较流行的IoC容器？ opensource

平时会关注开源软件的发展么？ opensource

HttpServlet类中有那些方法 servlet

jsp执行过程，大量使用jsp有什么问题？PermGen大小 servlet

servlet的生命周期 servlet

session的生命周期 servlet

如何在HttpSession过期的时候，清理你在HttpSession中保存的对象的资源占用？ servlet

notify()对应的方法是什么 thread

daemon线程的含义 thread

Thread的sleep方法和Object的wait方法有什么区别？ thread

解释synchronized thread

解释ThreadLocal thread

如何停止一个正在运行的线程？ thread

什么叫线程安全?servlet线程安全吗? thread

什么是Daemon线程？它有什么意义？ thread

怎么样写一个线程?用线程时的注意点? thread

JDK如何做到XMLParser的实现和接口无关？JDK是如何找到XMLParser的实现的？如何覆盖jdk1.4中的XMLParser实现？ xml

xml解析模型描述 xml

性能测试，容量测试，有没有？如何做？ 测试

有没有针对伸缩性的设计 架构

有没有针对性能的设计 架构

解释scalability与extensibility 架构

常见的排序算法有哪些？各有什么优缺点？ 理论

设计模式列举，解释使用场景 理论

PreparedStatement与Statement 数据库

数据库事务有哪几个隔离级别？请分别阐述 数据库

数据库相关的性能优化？sql，数据库本身，缓存？ 数据库

项目中碰到的问题，如何解决？ 问题解决

java应用性能优化，从哪些方面入手 性能优化





1. What is Java HashCode, If two objects has the same HashCode but not equal, can they existing in the same HashMap at the same time? Why?

2.What is the synchronized key word?

3.What is Java Garbage Collection

4.How does the JVM manage the class loader? What is the URLClassLoader and what does it used for?

5.What does static mean and when does JVM initialize the static variables?

6.What is the Immutable class? If we let you design one immutable class, which aspects you need to consider?

7.Why are Immutable classes a good defense against Concurrency problems?

8.What is the difference between Serializable and Externalizable interface in Java?

9.What is the ReentractLock?

10.What is the "Double-Checked Locking"? Why was it faulty before? And what has been done to make it work now?

11.What does the 'synchronized' keyword mean? What does the 'volatile' keyword mean?



一、麻烦请写出常用的Exception。
这道题目主要是考面试者的实际开发能力，特别是深度，也可以看出他过去常做的内容。
比如写了ClassNotFoundException，可能是做过ClassLoader动态加载的内容。
如果是写了ConcurrentModifiedException，可能是并发问题或者别的地方不足。
如果写了UnsupportOperationException，可能在设计方面有些基础或者经验。
如果写了SecurityException或者IlleagalException，说明做的内容比较深一些，更贴近底层。
一般来说，能写出20个以上，而且随意选择几个，大都能说的比较清楚，就是非常不错的了。
二、麻烦讲述一个有印象或者最难的Bug
这里主要是听面试者是否能够非常清楚细节地讲述一个Bug，包括如何发现，解决，反思，从这些内容上可以判断他是否在一线写代码，以及思维方式。
三、请说出几本觉得最有意义的技术书籍
如果有自己熟悉的书，就选择其中的点问就好了，如果没有，那么就请他讲述任何一本书的印象最深的点，如果讲述不出，大家就知道怎么处理了。
四、面试学生的时候，专业不同，对应的内容不同，怎么问
我一般会给他10分钟左右的时间，让他把毕业设计给我讲清楚，如果他对一个东西掌握地非常深，一定可以用简单的话语来讲清楚，否则只能说明他没有掌握好内容。
五、随便出一个问题，如Spring中如何对同名Bean加载时的处理
这类问题，不是一定要一个正确的答案，从设计的角度出发，不管是就近加载，还是直接抛出异常，又或者留给子类处理，都是合理的，关键是想听到面试人员的思考，对与错不重要，重要的是能够分析清楚不同方案的适合场景和相应问题。
