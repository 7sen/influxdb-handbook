# 前言

## InfluxDB v2.0 中文文档

文档不断完善中，如果感觉对亲有帮助，请给个**star！❥\(^\_-\)**  
  
项目地址: [https://github.com/7sen/influxdb-handbook](https://github.com/7sen/influxdb-handbook)

文档地址: [https://7sen.gitbook.io/influxdb-handbook](https://7sen.gitbook.io/influxdb-handbook/)

作者Github: [https://github.com/7sen](https://github.com/7sen)

### 文档介绍

官方 InfluxDB Docs 地址：[https://v2.docs.influxdata.com/v2.0/](https://v2.docs.influxdata.com/v2.0/)

编写文档时 InfluxDB 最新版本为：[v2.0.0-alpha.9 \[2019-05-01\]](https://v2.docs.influxdata.com/v2.0/reference/release-notes/)

InfluxDB v2.0 中文文档着手编写于2019年5月27日，作者之所以编写文档时机纯属偶然。

学习阿里开源中间件 Sentinel（分布式系统的流量防卫兵）时，了解到对于生产环境监控数据是需要持久化的， Sentinel 本省基于内存实现数据存储，数据持久化到数据库需要自行拓展，然而数据存储形式有很多，而对于监控数据持久化方式最佳方式则是时序数据库。

在最新 [DB-ENGINES](https://db-engines.com/en/ranking/time+series+dbms) 给出的时序数据库排名中，InfluxDB 稳居榜首，所以萌生了写下此文档决心。

