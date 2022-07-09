# 大数据电信客服项目
1.项目介绍

   通信运营商每时每刻会都会产生海量通信数据，如短信、月季度单和通话情况以及第三方服务资费等多种数据。同时除了要满足用户的实时查询和显示之外，还需要定时定期的对已有数据进行离线的分析处理。电信客服案例就是基于上述场景所模拟编程开发的大数据实战案例。 
*****
2.开发环境

    * Window+Linux

    * IntelliJ IDEA

    * jdk 1.8.0_311

    * Maven 3.8.5 

    * Flume 1.9.0

    * Kafka 2.6

    * Hbase 2.2.12

    * Hadoop 3.1.2

    * MySQL8

    * Echarts
 *****

3.项目架构

![image](https://github.com/AiRanXin/project-ct/blob/main/picture/%E9%A1%B9%E7%9B%AE%E6%9E%B6%E6%9E%84.png?raw=true)
    
    1.使用Hadoop作为大数据平台基础架构。 

    2.生成通讯数据文件。 

    3.使用flume框架采集通讯日记。 

    4.用kafka把日记放入Hbase存储。 

    5.读取Hbase的数据并用MapReduce进行计算处理。 

    6.使用yarn调度把mapreduce的结果输出MySQL。 

    7.通过webServer查询MySQL里的数据并用Echart图

*****
4.案例展示

   查询某人通话时长与通话次数并用Echart可视视化展示。
   
   ![image](https://raw.githubusercontent.com/AiRanXin/project-ct/main/picture/%E6%A1%88%E4%BE%8B%E5%B1%95%E7%A4%BA.png)
