## Filebeat安装部署及配置详解

### 一、概述

Filebeat是Beat成员之一，基于Go语言，无任何依赖，并且比logstash更加轻量，非常适合安装在生产机器上，不会带来过高的资源占用，轻量意味着简单，所以Filebeat并没有集成和logstash一样的正则处理功能，而是将收集的日志原样上报。

Filebeat工作原理图：





参考链接（后期实现）：
https://cloud.tencent.com/developer/article/1006051
