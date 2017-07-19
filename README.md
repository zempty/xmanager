# Xmanager 企业级多模块SSM项目
 背景：
 使用Java技术开发的工程项目，无论是数据处理系统还是Web网站，随着项目的不断发展，需求的不断细化与添加，工程项目中的代码越来越多，包结构也越来越复杂这时候工程的进展就会遇到各种问题：
（1）不同方面的代码之间相互耦合，这时候一系统出现问题很难定位到问题的出现原因，即使定位到问题也很难修正问题，可能在修正问题的时候引入更多的问题。
（2）多方面的代码集中在一个整体结构中，新入的开发者很难对整体项目有直观的感受，增加了新手介入开发的成本，需要有一个熟悉整个项目的开发者维护整个项目的结构（通常在项目较大且开发时间较长时这是很难做到的。
（3）开发者对自己或者他人负责的代码边界很模糊，这是复杂项目中最容易遇到的，导致的结果就是开发者很容易修改了他人负责的代码且代码负责人还不知道，责任追踪很麻烦。
 将一个复杂项目拆分成多个模块是解决上述问题的一个重要方法，多模块的划分可以降低代码之间的耦合性（从类级别的耦合提升到jar包级别的耦合），每个模块都可以是自解释的（通过模块名或者模块文档），模块还规范了代码边界的划分，开发者很容易通过模块确定自己所负责的内容。

 项目简介：

 本项目SSM部分代码主要使用了开源项目：http://git.oschina.net/wangzhixuan/spring-shiro-training 一个基于Shiro简单易用的权限管理系统

 主要用到的技术栈：

 spring

 mybatis

 springMVC

 Druid--阿里巴巴开源的数据库连接池

 Spring-cache

 Spring-data-redis

 Spring-Task

 Shiro

 Spring-cache-shiro

 hibernate-validator

 JWT--适用于分布式系统之间信息传递的安全规范

 easyUI--经典的管理系统前端框架，后期视情况可能更换成其他框架。

 maven profile多环境配置

 mysql 数据库

 rabbitMQ--消息服务

 redis--缓存数据库

