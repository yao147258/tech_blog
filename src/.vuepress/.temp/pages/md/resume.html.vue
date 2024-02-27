<template><div><h2 id="个人信息" tabindex="-1"><a class="header-anchor" href="#个人信息" aria-hidden="true">#</a> <strong>个人信息</strong></h2>
<ul>
<li>姓名:  姚凤桥</li>
<li>电话:  17671678756</li>
<li>邮箱:  1947846708@qq.com</li>
<li>毕业时间:  2022.06</li>
<li>工作时间:  2021.06</li>
<li>Gitee:  <a href="https://gitee.com/yaofengqiao">https://gitee.com/yaofengqiao</a></li>
</ul>
<h2 id="毕业院校" tabindex="-1"><a class="header-anchor" href="#毕业院校" aria-hidden="true">#</a> <strong>毕业院校</strong></h2>
<ul>
<li>2018.09 - 2022.06   湖北第二师范学院  软件工程   本科</li>
</ul>
<h2 id="专业技能" tabindex="-1"><a class="header-anchor" href="#专业技能" aria-hidden="true">#</a> <strong>专业技能</strong></h2>
<ul>
<li>熟练掌握 Java 核心知识、JUC、HashMap、斐波那契散列等，具备良好的面向对象编程思想。</li>
<li>熟练掌握 Java 设计模式，如工厂、代理、组合、策略等设计模式，并善用设计原则构建可复用代码。</li>
<li>熟练使用 IDEA、Eclipse、Visual Studio Code、Navicat、PostMan、Git、Maven、SVN 等开发工具。</li>
<li>深入理解 JVM 底层原理，熟悉 JVM 各类垃圾收集器的使用及核心参数的调优，具备一定的 JVM 调优能力。</li>
<li><code v-pre>深入学习 Spring 核心流程模块，如IOC、AOP、依赖倒置等，掌握Spring解决复杂场景所需的分治、抽象和知识（设计模式、设计原则），能从核心原理上解决Spring场景问题。同时，具备基于 Spring 开发 SpringBoot Starter 的技能，减少研发成本，为复杂项目提供通用技术组件。</code></li>
<li><code v-pre>深入学习 MyBatis 核心流程模块，包括会话、反射、代理、事务和插件，熟练掌握 ORM 框架的设计思想、实现方式和应用价值。并根据需求结合 MyBatis 插件机制，开发企业所需的功能，如数据分页、数据库表路由、监控日志和数据安全等。</code></li>
<li>深入理解 Spring Boot，Spring Cloud 等微服务框架的设计原理及底层架构，熟悉各种微服务架构设计比如服务注册与发现，服务降级，限流，熔断，服务网关路由设计，服务安全认证架构。</li>
<li>熟悉 Dubbo、Zookeeper 等分布式服务协调与治理等技术。</li>
<li>熟练掌握 MySql，掌握 MySQL 主从同步，读写分离技术以及集群的搭建，具备一定的 SQL 调优能力。</li>
<li>深入理解 Redis 线程模型，熟练掌握 Redis 的核心数据结构的使用场景，熟悉各种缓存高并发的使用场景，比如缓存雪崩，缓存穿透等。</li>
<li>熟练掌握分布式场景中的常见的技术问题及解决，比如分布式锁，分布式事务，分布式 session，分布式任务调度。</li>
<li>熟悉 RabbitMQ、Kafka 等常用的消息中间件进行消息的异步数据处理。</li>
<li>了解分布式搜索引擎 ElasticSearch，并能基于 ELK+Kafka 搭建分布式日志收集系统，以及 x-pack-jdbc 的扩展使用。</li>
<li>熟悉 docker 常用命令，能够实现基于 docker+Jenkins 实现自动化部署</li>
<li>掌握 Linux 常用命令，了解 Nginx 服务器的反向代理、负载均衡、动静分离等。</li>
<li>熟练运用 DDD 四层架构领域驱动设计，构建出易于迭代和维护的工程架构，遵守整洁代码、洋葱架构设计思想。</li>
</ul>
<h2 id="工作经历" tabindex="-1"><a class="header-anchor" href="#工作经历" aria-hidden="true">#</a> <strong>工作经历</strong></h2>
<ul>
<li>公司: 杭州长孚科技有限公司</li>
<li>时间: 2023.08 - 至今</li>
<li>岗位: Java开发工程师</li>
<li>职责【可选】: 负责氧惠APP、团好单、公众号日常版本迭代，线上BUG修复等
<br/>
<br/></li>
<li>公司: 威派格智慧水务有限公司</li>
<li>时间: 2021.06 - 2023.07</li>
<li>岗位: Java开发工程师</li>
<li>职责【可选】: 负责水司账务系统日常迭代、线上BUG修复等</li>
</ul>
<h2 id="项目经验" tabindex="-1"><a class="header-anchor" href="#项目经验" aria-hidden="true">#</a> <strong>项目经验</strong></h2>
<h3 id="_1-openai助手-openai营销平台" tabindex="-1"><a class="header-anchor" href="#_1-openai助手-openai营销平台" aria-hidden="true">#</a> 1. OpenAI助手 &amp; OpenAI营销平台</h3>
<ul>
<li>项目描述：此项目以应用AI为主，通过公众号鉴权、支付宝支付、对接多种AI大模型。提供了AI流式问答服务，为日常开发提效</li>
<li>项目架构：采用DDD领域驱动设计，将项目分为trigger、app、domain、infrastructure、types模块，涵盖了AI、账户、认证授权、规则校验、公众号、订单、产品等领域模型</li>
<li>核心技术：SpringBoot、MyBatis、Redis、Shiro、JWT、Guava EventBus、OKHttp3、DashScope(通义千问)大模型、支付宝支付等</li>
<li>项目部署：CenterOS7.9、Nginx、Docker、阿里云云效Devops、SpringBootActuator、Prometheus、Grafana、Loki</li>
<li>项目地址：<a href="http://openai.yaofengqiao.top">http://openai.yaofengqiao.top</a></li>
<li>核心职责：
<ul>
<li>项目架构搭建，采用DDD设计代码模块，领域模型拆分</li>
<li>Shiro + JWT 实现认证授权</li>
<li>使用SpringMVC ResponseBodyEmitter实现后端接口的流式应答(事件流)</li>
<li>使用模板方法模式定义AI问答的标准流程</li>
<li>自定义一系列规则校验器，在AI问答标准流程中，对实际调用AI接口方法做前置处理，例如敏感过滤、每分钟调用频率限制、黑名单限制、额度限制等</li>
<li>对接多ChatGPT、通义千问、ChatGLM(智谱AI)，在对接ChatGLM时设计独立的SDK，在实现上采用了 Session
会话模型进行处理，以及通过工厂处理服务。在细节上，采用了 OKHttp3 框架完成模型对接，这样的方式更好扩展，代码也更易于维护。</li>
<li>在整套工程的代码设计实现中，采用了较多抽象的思想和设计模式(模板方法、策略模式、工厂模式等)，来解决各类场景问题。</li>
<li>对接支付宝支付，完成从商品库、下单支付、异步发货、掉单补偿等核心流程实现。让用户可以在线购买AI问答额度。</li>
<li>对接微信公众号</li>
<li>购买阿里云服务器、申请域名、使用云效创建Devops流水线、部署配置Nginx、Mysql、Redis、Docker Container(可视化管理Docker容器)、
Prometheus(服务器数据收集)、Grafana(可视化监控)、Loki(日志收集)</li>
</ul>
</li>
</ul>
<h3 id="_2-氧惠商城app" tabindex="-1"><a class="header-anchor" href="#_2-氧惠商城app" aria-hidden="true">#</a> 2. 氧惠商城APP</h3>
<ul>
<li>项目描述：一站式电商导购、推广平台，包括了APP、H5、小程序、公众号，用户通过氧惠APP购买淘宝、京东等各大主流电商平台商品会获得返利金额，除此之外，
APP还包含了特惠话费电费充值、在线点单、本地生活等丰富的返利场景，争取让用户省的更多</li>
<li>项目架构：采用经典MVC模型、微服务设计理念来架构代码，项目分为portal、member、account、message、gateway、eureka、apollo等工程</li>
<li>核心技术：SpringBoot、SpringCloud、Apollo、Eureka、Shiro、Mysql、Redis、RabbitMQ、Redisson、ElasticSearch、OSS、Flink、支付宝支付、微信支付等</li>
<li>项目部署：阿里云Ubuntu 20.04、阿里云SLS(日志服务)、阿里云DMS(数据库管理服务)、Nginx、Docker、Gateway、Eureka、Jenkins CI/CD、Gitlab等</li>
<li>项目地址：<a href="http://h5.yanghuimall.com/pages/index/index">http://h5.yanghuimall.com/pages/index/index</a></li>
<li>核心职责：
<ul>
<li>APP首页商品搜索，使用策略 + 工厂模式设计代码，完成了包含了关键词搜索、全网搜索、指定平台搜索、商品排序等功能。</li>
<li>淘礼金充值(支付宝)，实现本地订单创建、请求支付渠道创建订单、下单支付、支付成功异步回调、回调成功后异步发货、统一收单接口进行掉单补偿等流程，以此让用户更好的推广自己的商品。</li>
<li>用户上下级关系建立，用户注册时需要填写邀请码，根据填写的邀请码在用户注册时，建立好整个系统里用户的邀请链路关系(用户链路关系到系统核心的分佣流程)</li>
<li>用户升级规则配置(用户等级包括会员等级、运营商等级)、用户升级实现，使用模板方法 + 策略模式定义标准流程，统一会员等级和运营商等级升级流程。
定义一系列升级规则匹配器，使用职责链模式来匹配当前等级的升级条件是否满足，如果满足就为用户升级
(升级方法由模板类的abstract定义，至于会员等级、运营商等级具体该如何操作交给子类实现)，
在模板方法定义升级完成的后置处理，用于扩展一些功能，例如升级后的APP消息推送、触发上级用户的升级流程等。</li>
<li>系统订单同步(分为生产者、消费者)，生产端使用工厂模式、自定义系统核心线程池来定时同步各大电商平台订单，解析为系统统一的Order模型后，发送MQ消息。
消费端使用Redisson加上订单粒度的分布式锁，避免并发带来的订单数据错误的问题，代码结构上使用状态模式将处理订单状态变化逻辑解耦，
同时处理状态变化时保证订单消费的幂等性，以及消除MQ消息无序消费带来的问题。</li>
<li>微信公众号开发，公众号用户注册、登录、授权、商品转链、客服消息、订单查询等，为无APP用户提供更加方便的使用方式。</li>
</ul>
</li>
</ul>
</div></template>


