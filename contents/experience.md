<!-- ### **Software Engineer Intern**  
**January 2025 – June 2025 | ByteDance**  

Worked on the development and optimization of large-scale recommendation systems, focusing on algorithm improvements and system efficiency enhancements. Contributed to real-time data processing pipelines and model optimization for personalized content delivery.

#### Key Contributions:  
- Developed and optimized recommendation algorithms to enhance user engagement and content relevance.  
- Designed and implemented real-time data processing workflows to improve model inference efficiency.  
- Conducted A/B testing and performance analysis to refine recommendation strategies based on user behavior data.  

--- -->

### **电池安全云端预警算法及测试开发**  
**2023年12月 – 2025年6月 | 问界系列**  

针对新能源汽车的电池热安全问题，开发了一个电池安全预警云平台。系统实时监控电池的运行状态，包括温度、压力、气体和声音数据，并更新对应的预警信息。平台支持多车管理、实时监控、历史数据查询和数据可视化展示，为新能源汽车运行安全提供保障。

#### 主要贡献:  
- 使用Netty构建WebSocket服务，提升并发处理能力。  
- 基于Redis实现分布式心跳检测。  
- 使用Kafka实现数据流处理，解决数据积压问题。
- 利用Redis设计优先级队列实现消息分级，结合Redisson分布式锁保证高优先级消息的顺序处理。


### **重庆大学“快乐食间”校园送餐系统**  
**2024年10月 – 2025年3月 | 校园项目**  

本项目是一个为重庆大学在校师生提供校园食堂点餐送餐服务的平台，包括系统管理后台和用户端（微信小程序）两个部分。系统管理后台可以对食堂各窗口、员工、菜品、订单等信息进行维护管理；用户端可以在线浏览菜品、添加购物车、下单等，由学生兼职完成送餐上门服务。

#### 主要贡献:  
- 使用Redis，采用一主两从+哨兵的集群方案，缓存营业状态、菜品分类等信息，解决了双写一致性问题。  
- 使用工厂模式和策略模式实现布隆过滤器解决缓存穿透问题。  
- 通过乐观锁解决超卖问题。
- 使用JWT令牌，用自定义拦截器完成用户认证，通过 ThreadLocal 来优化鉴权逻辑。
- 基于Redis，使用防重Token+lua脚本进行幂等性校验，防止订单重复提交。