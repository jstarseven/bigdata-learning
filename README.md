# bigdata-learning
![bigdata-learning](docs/pictures/jlz.png)



大数据开发抱团学习平台
===============

- 当前最新版本： 1.0.0（发布日期：20190812）
- 微信交流群 ：  添加kinyseven，备注：“进大数据开发抱团学习群”


项目介绍：
-----------------------------------

<h3 align="center">BigData Learning</h3>

本项目针对目前正在自学大数据开发技术的人或者是目前对大数据开发感兴趣准备自学的人，大家一起建立联系，相互学习，共同提高，相互监督，
希望参与的每个人都能有或多或少的收获。
目前已经建立微信学习交流群，群内人员大部分是新手，部分人员目前正在从事大数据相关的工作，还有部分是在校学生，
本着互利互惠的原则，大家友好交流！

<br/>

 借鉴：github.com/heibaiying/BigData-Notes

<table>
    <tr>
      <th><img width="50px" src="docs/pictures/hadoop.jpg"></th>
      <th><img width="50px" src="docs/pictures/hive.jpg"></th>
      <th><img width="50px" src="docs/pictures/spark.jpg"></th>
       <th><img width="50px" src="docs/pictures/storm.png"></th>
         <th><img width="50px" src="docs/pictures/flink.png"></th>
         <th><img width="50px" src="docs/pictures/hbase.png"></th>
      <th><img width="50px" src="docs/pictures/kafka.png"></th>
      <th><img width="50px" src="docs/pictures/zookeeper.jpg"></th>
      <th><img width="50px" src="docs/pictures/flume.png"></th>
      <th><img width="50px" src="docs/pictures/sqoop.png"></th>
      <th><img width="50px" src="docs/pictures/azkaban.png"></th>
      <th><img width="50px" src="docs/pictures/scala.jpg"></th>
    </tr>
    <tr>
      <td align="center"><a href="#一hadoop">Hadoop</a></td>
      <td align="center"><a href="#二hive">Hive</a></td>
      <td align="center"><a href="#三spark">Spark</a></td>
      <td align="center"><a href="#四storm">Storm</a></td>
      <td align="center"><a href="#五flink">Flink</a></td>
      <td align="center"><a href="#六hbase">HBase</a></td>
      <td align="center"><a href="#七kafka">Kafka</a></td>
      <td align="center"><a href="#八zookeeper">Zookeeper</a></td>
      <td align="center"><a href="#九flume">Flume</a></td>
      <td align="center"><a href="#十sqoop">Sqoop</a></td>
      <td align="center"><a href="#十一azkaban">Azkaban</a></td>
      <td align="center"><a href="#十二scala">Scala</a></td>
    </tr>
  </table>
<br/>

## 一、Hadoop

1. [分布式文件存储系统 —— HDFS](docs/notes/Hadoop-HDFS.md)
2. [分布式计算框架 —— MapReduce](docs/notes/Hadoop-MapReduce.md)
3. [集群资源管理器 —— YARN](docs/notes/Hadoop-YARN.md)
4. [Hadoop 单机伪集群环境搭建](docs/notes/installation/Hadoop单机环境搭建.md)
5. [Hadoop 集群环境搭建](docs/notes/installation/Hadoop集群环境搭建.md)
6. [HDFS 常用 Shell 命令](docs/notes/HDFS常用Shell命令.md)
7. [HDFS Java API 的使用](docs/notes/HDFS-Java-API.md)
8. [基于 Zookeeper 搭建 Hadoop 高可用集群](docs/notes/installation/基于Zookeeper搭建Hadoop高可用集群.md)

## 二、Hive

1. [Hive 简介及核心概念](docs/notes/Hive简介及核心概念.md)
2. [Linux 环境下 Hive 的安装部署](docs/notes/installation/Linux环境下Hive的安装部署.md)
4. [Hive CLI 和 Beeline 命令行的基本使用](docs/notes/HiveCLI和Beeline命令行的基本使用.md)
6. [Hive 常用 DDL 操作](docs/notes/Hive常用DDL操作.md)
7. [Hive 分区表和分桶表](docs/notes/Hive分区表和分桶表.md)
8. [Hive 视图和索引](docs/notes/Hive视图和索引.md)
9. [Hive常用 DML 操作](docs/notes/Hive常用DML操作.md)
10. [Hive 数据查询详解](docs/notes/Hive数据查询详解.md)

## 三、Spark

**Spark Core :**

1. [Spark 简介](docs/notes/Spark简介.md)
2. [Spark 开发环境搭建](docs/notes/installation/Spark开发环境搭建.md)
4. [弹性式数据集 RDD](docs/notes/Spark_RDD.md)
5. [RDD 常用算子详解](docs/notes/Spark_Transformation和Action算子.md)
5. [Spark 运行模式与作业提交](docs/notes/Spark部署模式与作业提交.md)
6. [Spark 累加器与广播变量](docs/notes/Spark累加器与广播变量.md)
7. [基于 Zookeeper 搭建 Spark 高可用集群](docs/notes/installation/Spark集群环境搭建.md)

**Spark SQL :**

1. [DateFrame 和 DataSet ](docs/notes/SparkSQL_Dataset和DataFrame简介.md)
2. [Structured API 的基本使用](docs/notes/Spark_Structured_API的基本使用.md)
3. [Spark SQL 外部数据源](docs/notes/SparkSQL外部数据源.md)
4. [Spark SQL 常用聚合函数](docs/notes/SparkSQL常用聚合函数.md)
5. [Spark SQL JOIN 操作](docs/notes/SparkSQL联结操作.md)

**Spark Streaming ：**

1. [Spark Streaming 简介](docs/notes/Spark_Streaming与流处理.md)
2. [Spark Streaming 基本操作](docs/notes/Spark_Streaming基本操作.md)
3. [Spark Streaming 整合 Flume](docs/notes/Spark_Streaming整合Flume.md)
4. [Spark Streaming 整合 Kafka](docs/notes/Spark_Streaming整合Kafka.md)

## 四、Storm

1. [Storm 和流处理简介](docs/notes/Storm和流处理简介.md)
2. [Storm 核心概念详解](docs/notes/Storm核心概念详解.md)
3. [Storm 单机环境搭建](docs/notes/installation/Storm单机环境搭建.md)
4. [Storm 集群环境搭建](docs/notes/installation/Storm集群环境搭建.md)
5. [Storm 编程模型详解](docs/notes/Storm编程模型详解.md)
6. [Storm 项目三种打包方式对比分析](docs/notes/Storm三种打包方式对比分析.md)
7. [Storm 集成 Redis 详解](docs/notes/Storm集成Redis详解.md)
8. [Storm 集成 HDFS/HBase](docs/notes/Storm集成HBase和HDFS.md)
9. [Storm 集成 Kafka](docs/notes/Storm集成Kakfa.md)

## 五、Flink

TODO

## 六、HBase

1. [Hbase 简介](docs/notes/Hbase简介.md)
2. [HBase 系统架构及数据结构](docs/notes/Hbase系统架构及数据结构.md)
3. [HBase 基本环境搭建 (Standalone /pseudo-distributed mode)](docs/notes/installation/HBase单机环境搭建.md)
4. [HBase 集群环境搭建](docs/notes/installation/HBase集群环境搭建.md)
5. [HBase 常用 Shell 命令](docs/notes/Hbase_Shell.md)
6. [HBase Java API](docs/notes/Hbase_Java_API.md)
7. [Hbase 过滤器详解](docs/notes/Hbase过滤器详解.md)
8. [HBase 协处理器详解](docs/notes/Hbase协处理器详解.md)
9. [HBase 容灾与备份](docs/notes/Hbase容灾与备份.md)
10. [HBase的 SQL 中间层 —— Phoenix](docs/notes/Hbase的SQL中间层_Phoenix.md)
11. [Spring/Spring Boot 整合 Mybatis + Phoenix](docs/notes/Spring+Mybtais+Phoenix整合.md)

## 七、Kafka

1. [Kafka 简介](docs/notes/Kafka简介.md)
2. [基于 Zookeeper 搭建 Kafka 高可用集群](docs/notes/installation/基于Zookeeper搭建Kafka高可用集群.md)
3. [Kafka 生产者详解](docs/notes/Kafka生产者详解.md)
4. [Kafka 消费者详解](docs/notes/Kafka消费者详解.md)
5. [深入理解 Kafka 副本机制](docs/notes/Kafka深入理解分区副本机制.md)

## 八、Zookeeper

1. [Zookeeper 简介及核心概念](docs/notes/Zookeeper简介及核心概念.md)
2. [Zookeeper 单机环境和集群环境搭建](docs/notes/installation/Zookeeper单机环境和集群环境搭建.md) 
3. [Zookeeper 常用 Shell 命令](docs/notes/Zookeeper常用Shell命令.md)
4. [Zookeeper Java 客户端 —— Apache Curator](docs/notes/Zookeeper_Java客户端Curator.md)
5. [Zookeeper  ACL 权限控制](docs/notes/Zookeeper_ACL权限控制.md)

## 九、Flume

1. [Flume 简介及基本使用](docs/notes/Flume简介及基本使用.md)
2. [Linux 环境下 Flume 的安装部署](docs/notes/installation/Linux下Flume的安装.md)
3. [Flume 整合 Kafka](docs/notes/Flume整合Kafka.md)

## 十、Sqoop

1. [Sqoop 简介与安装](docs/notes/Sqoop简介与安装.md)
2. [Sqoop 的基本使用](docs/notes/Sqoop基本使用.md)

## 十一、Azkaban

1. [Azkaban 简介](docs/notes/Azkaban简介.md)
2. [Azkaban3.x 编译及部署](docs/notes/installation/Azkaban_3.x_编译及部署.md)
3. [Azkaban Flow 1.0 的使用](docs/notes/Azkaban_Flow_1.0_的使用.md)
4. [Azkaban Flow 2.0 的使用](docs/notes/Azkaban_Flow_2.0_的使用.md)

## 十二、Scala

1. [Scala 简介及开发环境配置](docs/notes/Scala简介及开发环境配置.md)
2. [基本数据类型和运算符](docs/notes/Scala基本数据类型和运算符.md)
3. [流程控制语句](docs/notes/Scala流程控制语句.md)
4. [数组 —— Array](docs/notes/Scala数组.md)
5. [集合类型综述](docs/notes/Scala集合类型.md)
6. [常用集合类型之 —— List & Set](docs/notes/Scala列表和集.md)
7. [常用集合类型之 —— Map & Tuple](docs/notes/Scala映射和元组.md)
8. [类和对象](docs/notes/Scala类和对象.md)
9. [继承和特质](docs/notes/Scala继承和特质.md)
10. [函数 & 闭包 & 柯里化](docs/notes/Scala函数和闭包.md)
11. [模式匹配](docs/notes/Scala模式匹配.md)
12. [类型参数](docs/notes/Scala类型参数.md)
13. [隐式转换和隐式参数](docs/notes/Scala隐式转换和隐式参数.md)

交流互动
-----------------------------------

- 微信交流群 ：  添加kinyseven，备注：“进大数据开发抱团学习群”

- 反馈问题：  [反馈问题，请按格式发Issues]()

- 参与开源：  [参与人员，相互监督，相互学习，共同提高！！！]()

- 每天一小时： [根据自身时间安排]()

