---
title: 个人简历
index: false
icon: laptop-code
category:
  - 自我介绍
  - 专业技能
  - 项目经验
---

## **个人信息**

- 姓名:&nbsp;&nbsp;姚凤桥
- 电话:&nbsp;&nbsp;17671678756
- 邮箱:&nbsp;&nbsp;1947846708@qq.com
- 毕业时间:&nbsp;&nbsp;2022.06
- 工作时间:&nbsp;&nbsp;2021.06
- Gitee:&nbsp;&nbsp;<a href="https://gitee.com/yaofengqiao">https://gitee.com/yaofengqiao</a>

[//]: # (- 开源项目：[vo2dto]&#40;https://bugstack.cn/md/product/idea-plugin/vo2dto.html&#41; - IDEA Plugin 自动转换对象插件，5.4k 下载使用)

## **毕业院校**

- 2018.09 - 2022.06 &nbsp; 湖北第二师范学院&nbsp; 软件工程 &nbsp; 本科

[//]: # (- 荣誉、成绩)

## **专业技能**

- 熟练掌握 Java 核心知识、JUC、HashMap、斐波那契散列等，具备良好的面向对象编程思想。
- 熟练掌握 Java 设计模式，如工厂、代理、组合、策略等设计模式，并善用设计原则构建可复用代码。
- 熟练使用 IDEA、Eclipse、Visual Studio Code、Navicat、PostMan、Git、Maven、SVN 等开发工具。
- 深入理解 JVM 底层原理，熟悉 JVM 各类垃圾收集器的使用及核心参数的调优，具备一定的 JVM 调优能力。
- `深入学习 Spring 核心流程模块，如IOC、AOP、依赖倒置等，掌握Spring解决复杂场景所需的分治、抽象和知识（设计模式、设计原则），能从核心原理上解决Spring场景问题。同时，具备基于 Spring 开发 SpringBoot Starter 的技能，减少研发成本，为复杂项目提供通用技术组件。`
- `深入学习 MyBatis 核心流程模块，包括会话、反射、代理、事务和插件，熟练掌握 ORM 框架的设计思想、实现方式和应用价值。并根据需求结合 MyBatis 插件机制，开发企业所需的功能，如数据分页、数据库表路由、监控日志和数据安全等。`
- 深入理解 Spring Boot，Spring Cloud 等微服务框架的设计原理及底层架构，熟悉各种微服务架构设计比如服务注册与发现，服务降级，限流，熔断，服务网关路由设计，服务安全认证架构。
- 熟悉 Dubbo、Zookeeper 等分布式服务协调与治理等技术。
- 熟练掌握 MySql，掌握 MySQL 主从同步，读写分离技术以及集群的搭建，具备一定的 SQL 调优能力。
- 深入理解 Redis 线程模型，熟练掌握 Redis 的核心数据结构的使用场景，熟悉各种缓存高并发的使用场景，比如缓存雪崩，缓存穿透等。
- 熟练掌握分布式场景中的常见的技术问题及解决，比如分布式锁，分布式事务，分布式 session，分布式任务调度。
- 熟悉 RabbitMQ、Kafka 等常用的消息中间件进行消息的异步数据处理。
- 了解分布式搜索引擎 ElasticSearch，并能基于 ELK+Kafka 搭建分布式日志收集系统，以及 x-pack-jdbc 的扩展使用。
- 熟悉 docker 常用命令，能够实现基于 docker+Jenkins 实现自动化部署
- 掌握 Linux 常用命令，了解 Nginx 服务器的反向代理、负载均衡、动静分离等。
- 熟练运用 DDD 四层架构领域驱动设计，构建出易于迭代和维护的工程架构，遵守整洁代码、洋葱架构设计思想。

## **工作经历**

- 公司: 杭州长孚科技有限公司
- 时间: 2023.08 - 至今
- 岗位: Java开发工程师
- 职责【可选】: 负责氧惠APP、团好单、公众号日常版本迭代，线上BUG修复等
  <br/>
  <br/>
- 公司: 威派格智慧水务有限公司
- 时间: 2021.06 - 2023.07
- 岗位: Java开发工程师
- 职责【可选】: 负责水司账务系统日常迭代、线上BUG修复等

## **项目经验**

### 1. OpenAI助手 & OpenAI营销平台

- 项目描述：此项目以应用AI为主，通过公众号鉴权、支付宝支付、对接多种AI大模型。提供了AI流式问答服务，为日常开发提效
- 项目架构：采用DDD领域驱动设计，将项目分为trigger、app、domain、infrastructure、types模块，涵盖了AI、账户、认证授权、规则校验、公众号、订单、产品等领域模型
- 核心技术：SpringBoot、MyBatis、Redis、Shiro、JWT、Guava EventBus、OKHttp3、DashScope(通义千问)大模型、支付宝支付等
- 项目部署：CenterOS7.9、Nginx、Docker、阿里云云效Devops、SpringBootActuator、Prometheus、Grafana、Loki
- 项目地址：<a href="http://openai.yaofengqiao.top">http://openai.yaofengqiao.top</a>
- 核心职责：
    - 项目架构搭建，采用DDD设计代码模块，领域模型拆分
    - Shiro + JWT 实现认证授权
    - 使用SpringMVC ResponseBodyEmitter实现后端接口的流式应答(事件流)
    - 使用模板方法模式定义AI问答的标准流程
    - 自定义一系列规则校验器，在AI问答标准流程中，对实际调用AI接口方法做前置处理，例如敏感过滤、每分钟调用频率限制、黑名单限制、额度限制等
    - 对接多ChatGPT、通义千问、ChatGLM(智谱AI)，在对接ChatGLM时设计独立的SDK，在实现上采用了 Session
      会话模型进行处理，以及通过工厂处理服务。在细节上，采用了
      OKHttp3 框架完成模型对接，这样的方式更好扩展，代码也更易于维护。
    - 在整套工程的代码设计实现中，采用了较多抽象的思想和设计模式(模板方法、策略模式、工厂模式等)，来解决各类场景问题。
    - 对接支付宝支付，完成从商品库、下单支付、异步发货、掉单补偿等核心流程实现。让用户可以在线购买AI问答额度。
    - 对接微信公众号
    - 购买阿里云服务器、申请域名、使用云效创建Devops流水线、部署配置Nginx、Mysql、Redis、Docker Container(可视化管理Docker容器)、
      Prometheus(服务器数据收集)、Grafana(可视化监控)、Loki(日志收集)

### 2. 氧惠商城APP

- 项目描述：一站式电商导购、推广平台，包括了APP、H5、小程序、公众号，用户通过氧惠APP购买淘宝、京东等各大主流电商平台商品会获得返利金额，除此之外，
  APP还包含了特惠话费电费充值、在线点单、本地生活等丰富的返利场景，争取让用户省的更多
- 项目架构：采用经典MVC模型、微服务设计理念来架构代码，项目分为portal、member、account、message、gateway、eureka、apollo等工程
- 核心技术：SpringBoot、SpringCloud、Apollo、Mysql、Redis、ElasticSearch、Flink、
  Starter中间件实现了熔断、降级、限流、切量、白名单等服务治理功能，减少了开发工作量和出错风险。利用SpringBoot的自动化配置机制简化了集成和使用，并提供了可扩展接口，以满足不同场景的需求。
- 项目地址：<a href="http://h5.yanghuimall.com/pages/index/index">http://h5.yanghuimall.com/pages/index/index</a>
- 核心职责：
    - 鉴于组内同类需求的重复开发，设计并实现服务治理 SpringBoot Starter 中间件，提高开发效率和降低重复开发成本。
      该中间件的核心功能包括服务治理中的熔断、降级、限流、切量和白名单等。
    - 通过利用SpringBoot的自动化配置机制，该中间件可以简化集成和使用，同时提供足够的配置选项以满足不同场景的需求。
    - 此外，该中间件还提供了可扩展的接口，方便用户根据自身需求扩展功能，从而更好地满足不同的业务需求。
