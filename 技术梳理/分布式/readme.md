# 0. 集中式系统
在学习分布式系统之前, 我们先了解一下什么是集中式系统.
> "传统集中式系统中整个项目所有的东西都在一个应用里面。一个网站就是一个应用，当系统压力较大时，只能横向扩展，增加多个服务器或者多个容器去做负载均衡，避免单点故障而影响到整个系统。集中式最明显的优点就是开发，测试，运维会比较方便，不用考虑复杂的分布式环境。弊端也很明显，系统大而复杂、不易扩展、难于维护，每次更新都必须更新所有的应用".
---摘自:[我理解的分布式系统](https://juejin.im/post/5c7cd6eee51d457c042d4b52)


# 1. 什么是分布式系统(distributed system)?
> "A distributed system is one in which components located at networked computers
communicate and coordinate their actions only by passing messages." (分布式系统是各部分组件位于网络, 只通过传递消息来通信和协调动作的系统)

# 附: 参考
- [大型分布式网站架构技术总结](https://www.cnblogs.com/itfly8/p/4967966.html)
- [浅谈大型分布式Web系统的架构演进](https://juejin.im/post/5b4c4e566fb9a04f83464102)
- [我理解的分布式系统](https://juejin.im/post/5c7cd6eee51d457c042d4b52)
- [为什么需要分布式配置中心](https://blog.csdn.net/xlgen157387/article/details/82840553)
- [详解RPC远程调用和消息队列MQ的区别](https://juejin.im/post/5c3486caf265da615705a8b9)
- [spring微服务架构设计与轻量级微服务架构及最佳部署](https://juejin.im/post/5ae9ce71f265da0ba266ce55)
- [大型分布式网站架构实战项目分析](https://zhuanlan.zhihu.com/p/62229232)
- [远程调用服务(RPC)和消息队列(Message Queue)对比及其适用/不适用场合分析](https://blog.csdn.net/cfydaniel/article/details/44621163)
