# 什么是Elasticsearch？

> 原文：[What is Elasticsearch? | Elasticsearch Guide [7.10] | Elastic](https://www.elastic.co/guide/en/elasticsearch/reference/7.10/elasticsearch-intro.html)

***你知道的，为了搜索（也为了分析）***

Elasticsearch是位于Elastic Stack核心的分布式搜索和分析引擎。 Logstash and Beats有助于你收集，聚合和丰富数据，并存储到Elasticsearch中。Kibana使得你可以交互式地探索，可视化，分享您数据的见解，管理并监控堆栈（stack）。ElasticSearch正是构建索引，搜索和分析的神奇所在。

Elasticsearch提供了对全类型数据近乎实时的搜索和分析。无论你是结构化或者非结构化文本，数值数据或者地理空间数据，Elasticsearch可以高效地存储并构建索引以支持快速搜索。你不止可以简单的进行数据检索，还能通用聚合信息去发现数据的趋势和模式。随着数据和查询量的增长，Elasticsearch的分布式特性使得你的部署可以无缝地随之成长。

虽然不是每个问题都是搜索问题，但是Elasticsearch兼具速度和灵活性，可满足各类使用场景的数据处理需求：

* 在APP或网站添加搜索框

* 存储并分析日志，指标和安全事件数据

* 使用机器学习实时自动模拟数据行为

* 使用Elasticsearch的空间信息系统（GIS）来管理，集成和分析空间数据

* 使用Elasticsearch作为存储和处理生物信息学的遗传数据的工具

人们运用搜索的创新方式总能让我们惊叹不已。但无论你的使用场景与其中某类相似，还是打算借助 Elasticsearch 攻克全新难题，在 Elasticsearch 中处理数据、文档和索引的核心逻辑始终一致。
