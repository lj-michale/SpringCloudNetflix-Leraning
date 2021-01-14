
spring cloud微服务有哪些组件?
```$xslt
Eureka : 服务注册与发现
Ribbon : 负载均衡
Hystrix : 服务保护与熔断机制
Feign : 声明式接口
Zuul/Gateway : 网关
Integration/Stream : MQ接口绑定
Bus : 事件监听
Sleuth+Zipkin : 分布式链路追踪
Config : 配置中心 (可以使用Apollo替代)
可替换组件：注册中心、配置中心：Zookeeper、Consul
```