# 第一部分：数据系统基础
# Section 1: Data System Basis
# Part 1: Foundations of Data System

本书前四章介绍了数据系统底层的基础概念，无论是在单台机器上运行的单点数据系统，还是分布在多台机器上的分布式数据系统都适用。
The previous four chapter of text introduce the basic concept of data system underlying, which can be used in single node data system runing on single machine, or in distributed system distributed in multiple machine.

The first four chapters go through the fundamental ideas that apply to all data systems, whether running on a single machine or distributed accross a cluster of machines.

1. [第一章](ch1.md) 将介绍本书使用的术语和方法。**可靠性，可伸缩性和可维护性** ，这些词汇到底意味着什么？如何实现这些目标？

   [chapter 1] introduce termology and method. **realibity, scalability and maintainability**, what does these word mean? how to achieve these goal?

   [chapter 1] introduces the terminology and approach that we are going to use throughout this book. It examines what actually mean by words like realiability, scalability, and maintainability, and how we can try to achieve these goal?

2. [第二章](ch2.md) 将对几种不同的 **数据模型和查询语言** 进行比较。从程序员的角度看，这是数据库之间最明显的区别。不同的数据模型适用于不同的应用场景。

    [chapter 2] compare dirrerent **data mode and query language**. from the perspective of programmer, this is the main difference between databases. different data mode is suitable for different application.

    [chapter] compares several different adta models and query languages-the most visible distinguishing factor between databases from a developer's point of view. We will see how different models are appropriate to different situations.

3. [第三章](ch3.md) 将深入 **存储引擎** 内部，研究数据库如何在磁盘上摆放数据。不同的存储引擎针对不同的负载进行优化，选择合适的存储引擎对系统性能有巨大影响。

    [chapter 3] deep in **storage engine**, study how the database distrubute data on the disk. different storage engine make some optimize for different load, choosing a suitable engine have curical impact to performance of system.

    [chapter 3] turns to the internals of storage engines and looks at how databases lay out data on disk. Different storage engines are optimized for different workloads, and choosing the right one can have a huge effect on performance.

4. [第四章](ch4) 将对几种不同的 **数据编码** 进行比较。特别研究了这些格式在应用需求经常变化、模式需要随时间演变的环境中表现如何。

    [chapter 4] compare different **data encode**. study how these format performer in application requirement change and pattern changing with time.

    [chapter 4] compares various formats for data encoding(serialization) and especially examines how they fare in an environment where application requirements change and schemas need to adapt over time.

第二部分将专门讨论在 **分布式数据系统** 中特有的问题。

    discus special problem in **distribute data system** in section 2.

    later, Pater II will return to the particular issues of distributed data systems.


## 目录
## contents


1. [可靠性、可伸缩性和可维护性](ch1.md)

    1. realiability, scalability and maintainability
2. [数据模型与查询语言](ch2.md)
    2. data mode and query language
3. [存储与检索](ch3.md)
    3. store and index
4. [编码与演化](ch4.md)
    4. encode and evolution


------

| 上一章             | 目录                            | 下一章                                       |
| ------------------ | ------------------------------- | -------------------------------------------- |
| [序言](preface.md) | [设计数据密集型应用](README.md) | [第一章：可靠性、可伸缩性和可维护性](ch1.md) |
