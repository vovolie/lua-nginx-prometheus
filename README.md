# lua-nginx-prometheus
这是一个监控Nginx流量的扩展程序.

## 介绍
基于Openresty和Prometheus、Consul、Grafana设计的，实现了针对域名和endpoint级别的流量统计，使用Consul做服务发现、KV存储，Grafana做性能图展示。

最终展现图

![](screenshot/grafana.png)