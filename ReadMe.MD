ELK入门使用-与springboot集成
---

博客地址：
https://blog.csdn.net/binyao02123202/article/details/80468623


####1. 什么是ELK

ELK是Elasticsearch + Logstash + Kibana 简称

####ELK平台：

    是一个完整的日志分析解决方案，由这三个开源工具构建而成：Elasticsearch、Logstash、Kibana。

    是一个分布式的搜索和分析引擎，可以用于全文检索、结构化检索和分析，并能将这三者结合起来。Elasticsearch 基于 Lucene 开发，现在是使用最广的开源搜索引擎之一。


    Elasticsearch：
    是一个分布式的搜索和分析引擎，可以用于全文检索、结构化检索和分析，并能将这三者结合起来。Elasticsearch 基于 Lucene 开发，现在是使用最广的开源搜索引擎之一。
    
    用于深度搜索和数据分析，它是基于Apache Lucene的分布式开源搜索引擎，无须预先定义数据结构就能动态地对数据进行索引；
    
   

    Logstash：
    简单来说就是一根具备实时数据传输能力的管道，负责将数据信息从管道的输入端传输到管道的输出端，与此同时这根管道还可以让你根据自己的需求在中间加上滤网，Logstash提供了很多功能强大的滤网以满足你的各种应用场景。
    
    用于日志集中管理，包括从多台服务器上传输和转发日志，并对日志进行丰富和解析，是一个数据管道，提供了大量插件来支持数据的输入和输出处理；

    Kibana：
    是一个开源的分析与可视化平台，设计出来用于和Elasticsearch一起使用的。你可以用kibana搜索、查看、交互存放在Elasticsearch索引里的数据，使用各种不同的图标、表格、地图等，kibana能够很轻易的展示高级数据分析与可视化。
    
    提供了强大而美观的数据可视化，Kibana完全使用HTML和Javascript编写，它利用Elasticsearch 的RESTful API来实现其强大的搜索能力，将结果显示位各种震撼的图形提供给最终的用户。

