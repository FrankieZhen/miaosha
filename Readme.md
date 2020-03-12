 项目描述：使用 Spring Boot 搭建后端，集成了Mybatis 和 Redis，实现了单点登录模块和商品秒杀模块。

1. 使用了 MySQL 做主从数据库，实现读写分离。 
2. 使用 Redis 预减库存。 
3. 使用 RabbitMQ 实现异步下单。 
4. 使用分布式session、MD5加盐加密实现登录功能。 
5. 使用 Redis 实现隐藏秒杀 URL、接口防刷。  