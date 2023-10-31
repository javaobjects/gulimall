<p align="center">
    <a href='https://docs.oracle.com/en/java/javase/8'><img alt="Java 8" src="./资料源码/docs/pics/Java8.png"></a>
    <a href='https://docs.spring.io/spring-boot/docs/2.6.2-SNAPSHOT/reference/html'><img alt="Spring Boot 2" src="https://img.shields.io/badge/Spring%20Boot%202-%23000000.svg?logo=springboot"></a>
    <a href='https://staging-cn.vuejs.org'><img alt="Vue 3" src="https://img.shields.io/badge/Vue%202%20-%232b3847.svg?logo=vue.js"></a><br/>
    <a href='#'><img alt="Github stars" src="https://img.shields.io/github/stars/201206030/novel?logo=github"></a>
    <a href='#'><img alt="Github forks" src="https://img.shields.io/github/forks/201206030/novel?logo=github"></a>
    <a href='#'><img alt="Gitee stars" src="https://gitee.com/novel_dev_team/novel/badge/star.svg?theme=gitee"></a>
    <a href='#'><img alt="Gitee forks" src="https://gitee.com/novel_dev_team/novel/badge/fork.svg?theme=gitee"></a>
</p>

# 谷粒商城

#### 开发环境

+ Windows

#### 配置环境

| 程序           | 版本        | 说明                       |
|--------------|-----------|--------------------------|
| Jdk          | 1.8.0 161 | Java 开发工具包               |
| Mysql        | 5.5.27    | 关系型数据库                   |
| Apache-maven | 3.9.0     | Java 项目管理和构建工具           |
| Nvm          | 1.10      | Node.js 版本管理器            |
| Node         | 8.12.0    | Node.js JavaScript 运行时环境 |

#### 开发工具

| 工具                       | 版本            | 说明                      |
|--------------------------|---------------|-------------------------|
| IDEA                     | 2022.3.2      | 后前端开发IDE                |
| Git                      | 2.24.1        | 代码托管平台                  |
| Google   Chrome          | 75.0.3770.100 | 浏览器、前端调试工具              |
| Navicat                  | 11.1.13       | 数据库连接工具                 |
| Postman                  | 7.1.0         | 接口测试工具                  |
| VMware   Workstation Pro | 14.1.3        | 虚拟机(未用到或许你会用到)          |
| PowerDesigner            | 15            | 数据库设计工具(未用到或许你会用到)      |
| SQLyog                   | 12.0.3        | 数据库连接工具 (未用到或许你会用到)     |
| Visio                    | 2013          | 时序图、流程图等绘制工具(未用到或许你会用到) |
| ProcessOn                | ——            | 架构图等绘制工具(未用到或许你会用到)     |
| XMind   ZEN              | 9.2.0         | 思维导图绘制工具(未用到或许你会用到)     |
| RedisDesktop             | 0.9.3.817     | redis客户端连接工具(未用到或许你会用到) |

#### 编码规范

- 规范方式：严格遵守阿里编码规约。
- 命名统一：简介最大程度上达到了见名知意。
- 分包明确：层级分明可快速定位到代码位置。
- 注释完整：描述性高大量减少了开发人员的代码阅读工作量。
- 工具规范：使用统一jar包避免出现内容冲突。
- 代码整洁：可读性、维护性高。

#### 包的结构

```
+- gulimall -- 
|   +- .gitignore -- 
|   +- LICENSE -- 
|   +- README.md -- 
|   +- 课件和文档 -- 
|   |   +- 基础篇 -- 
|   |   |   +- 课件 -- 
|   |   |   |   +- 01、分布式基础&项目环境搭建.pdf -- 
|   |   |   |   +- 02、SpringCloud组件.pdf -- 
|   |   |   |   +- 03、前端开发基础知识.pdf -- 
|   |   |   |   +- 04、商品服务.pdf -- 
|   |   |   |   +- 谷粒商城-分布式基础-图.pdf -- 
|   |   |   +- 资料 -- 
|   |   |   |   +- gmall_数据库设计.pdb -- 
|   |   |   |   +- gmall_数据库设计.pdm -- 
|   |   |   |   +- pom.xml -- 
|   |   |   |   +- 谷粒商城-微服务架构图.jpg -- 
|   |   +- 谷粒商城doc文档 -- 
|   |   |   +- 01 谷粒商城介绍.docx -- 
|   |   |   +- 02 谷粒架构.docx -- 
|   |   |   +- 03 谷粒前后端分离.docx -- 
|   |   |   +- 04 谷粒商品pms.docx -- 
|   |   |   +- 04 谷粒商品pms_FastDfs.docx -- 
|   |   |   +- 05 谷粒商品详情页.docx -- 
|   |   |   +- 06 全文搜索_elasticsearch6.0.docx -- 
|   |   |   +- 06 谷粒商品全文搜索.docx -- 
|   |   |   +- 07 谷粒商品购物车.docx -- 
|   |   |   +- 08 登录_单点登录.docx -- 
|   |   |   +- 08 登录_社交登陆.docx -- 
|   |   |   +- 09 谷粒订单提交.docx -- 
|   |   |   +- 10 谷粒支付.docx -- 
|   |   |   +- 11 支付订单库存消息Mq交互(分布式事务).docx -- 
|   |   |   +- 12 Mq延迟队列.docx -- 
|   |   |   +- 13 秒杀和限流的介绍.docx -- 
|   |   |   +- 14 docker+k8s的云容器概述.docx -- 
|   |   |   +- 与金融相关的业务问题.docx -- 
|   |   |   +- 电商项目的项目总结.docx -- 
|   |   +- 运维篇 -- 
|   |   |   +- 课件 -- 
|   |   |   |   +- K8S部署&DevOps.pdf -- 
|   |   +- 高级篇 -- 
|   |   |   +- 课件 -- 
|   |   |   |   +- 01、Reactive&WebFlux.pdf -- 
|   |   |   |   +- 02、接口幂等性.pdf -- 
|   |   |   |   +- 03、本地事务&分布式事务.pdf -- 
|   |   |   |   +- 04、性能与压力测试.pdf -- 
|   |   |   |   +- 05、缓存&分布式锁.pdf -- 
|   |   |   |   +- 06、ElasticSearch.pdf -- 
|   |   |   |   +- 07、异步&线程池.pdf -- 
|   |   |   |   +- 08、单点登录与社交登录.pdf -- 
|   |   |   |   +- 09、商城业务.pdf -- 
|   |   |   |   +- 10、RabbitMQ.pdf -- 
|   |   |   |   +- 10、RabbitMQ.pptx -- 
|   |   |   |   +- 11、支付.pdf -- 
|   |   |   |   +- 12、定时任务与分布式调度.pdf -- 
|   |   |   |   +- 13、ShardingSphere.pdf -- 
|   |   |   |   +- 14、SpringCloud组件.pdf -- 
|   |   |   |   +- mq对比.jpg -- 
|   |   |   |   +- usingthymeleaf.pdf -- 
|   |   |   |   +- 单点登录流程.png -- 
|   |   |   |   +- 消息队列流程.jpg -- 
|   |   |   |   +- 电商订单流程图.png -- 
|   |   |   |   +- 社交登录流程.png -- 
|   |   |   |   +- 订单确认页流程.png -- 
|   |   |   +- 资料图片 -- 
|   |   |   |   +- 谷粒商城-分布式高级-图.pdf -- 
|   |   |   |   +- 谷粒商城-微服务架构图.jpg -- 
|   +- 资料源码 -- 
|   |   +- docs -- 
|   |   |   +- gmall_数据库设计.pdb -- 
|   |   |   +- gmall_数据库设计.pdm -- 
|   |   |   +- pom.xml -- 
|   |   |   +- 代码 -- 
|   |   |   |   +- gulimall -- 
|   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   +- gulimall-common -- 
|   |   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   +- main -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- common -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- constant -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- ProductConstant.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- WareConstant.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- exception -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- BizCodeEnume.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- to -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberPrice.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuReductionTo.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuBoundTo.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- utils -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- Constant.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- PageUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- Query.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- R.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- RRException.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- valid -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- AddGroup.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- ListValue.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- ListValueConstraintValidator.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- UpdateGroup.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- UpdateStatusGroup.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- xss -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- HTMLFilter.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- SQLFilter.java -- 
|   |   |   |   |   |   |   +- test -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   +- gulimall-coupon -- 
|   |   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   +- main -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- coupon -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponHistoryController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponSpuCategoryRelationController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponSpuRelationController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeAdvController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeSubjectController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeSubjectSpuController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberPriceController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillPromotionController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSessionController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSkuNoticeController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSkuRelationController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuFullReductionController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuLadderController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuBoundsController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- dao -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponHistoryDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponSpuCategoryRelationDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponSpuRelationDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeAdvDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeSubjectDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeSubjectSpuDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberPriceDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillPromotionDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSessionDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSkuNoticeDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSkuRelationDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuFullReductionDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuLadderDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuBoundsDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- entity -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponHistoryEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponSpuCategoryRelationEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponSpuRelationEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeAdvEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeSubjectEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeSubjectSpuEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberPriceEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillPromotionEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSessionEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSkuNoticeEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSkuRelationEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuFullReductionEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuLadderEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuBoundsEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallCouponApplication.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponHistoryService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponSpuCategoryRelationService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponSpuRelationService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeAdvService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeSubjectService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeSubjectSpuService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- impl -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponHistoryServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponSpuCategoryRelationServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponSpuRelationServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeAdvServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeSubjectServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- HomeSubjectSpuServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberPriceServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillPromotionServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSessionServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSkuNoticeServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSkuRelationServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuFullReductionServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuLadderServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuBoundsServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberPriceService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillPromotionService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSessionService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSkuNoticeService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SeckillSkuRelationService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuFullReductionService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuLadderService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuBoundsService.java -- 
|   |   |   |   |   |   |   +- test -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- coupon -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallCouponApplicationTests.java -- 
|   |   |   |   |   +- gulimall-gateway -- 
|   |   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   +- main -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- gateway -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- config -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallCorsConfiguration.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallGatewayApplication.java -- 
|   |   |   |   |   |   |   +- test -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- gateway -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallGatewayApplicationTests.java -- 
|   |   |   |   |   +- gulimall-member -- 
|   |   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   +- main -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- member -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- GrowthChangeHistoryController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- IntegrationChangeHistoryController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberCollectSpuController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberCollectSubjectController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberLevelController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberLoginLogController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberReceiveAddressController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberStatisticsInfoController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- dao -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- GrowthChangeHistoryDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- IntegrationChangeHistoryDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberCollectSpuDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberCollectSubjectDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberLevelDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberLoginLogDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberReceiveAddressDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberStatisticsInfoDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- entity -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- GrowthChangeHistoryEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- IntegrationChangeHistoryEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberCollectSpuEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberCollectSubjectEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberLevelEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberLoginLogEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberReceiveAddressEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberStatisticsInfoEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- feign -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponFeignService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallMemberApplication.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- GrowthChangeHistoryService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- impl -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- GrowthChangeHistoryServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- IntegrationChangeHistoryServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberCollectSpuServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberCollectSubjectServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberLevelServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberLoginLogServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberReceiveAddressServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberStatisticsInfoServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- IntegrationChangeHistoryService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberCollectSpuService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberCollectSubjectService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberLevelService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberLoginLogService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberReceiveAddressService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberStatisticsInfoService.java -- 
|   |   |   |   |   |   |   +- test -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- member -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallMemberApplicationTests.java -- 
|   |   |   |   |   +- gulimall-order -- 
|   |   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   +- main -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- order -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderItemController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderOperateHistoryController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderReturnApplyController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderReturnReasonController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderSettingController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PaymentInfoController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- RefundInfoController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- dao -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderItemDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderOperateHistoryDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderReturnApplyDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderReturnReasonDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderSettingDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PaymentInfoDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- RefundInfoDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- entity -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderItemEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderOperateHistoryEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderReturnApplyEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderReturnReasonEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderSettingEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PaymentInfoEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- RefundInfoEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallOrderApplication.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- impl -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderItemServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderOperateHistoryServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderReturnApplyServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderReturnReasonServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderSettingServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PaymentInfoServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- RefundInfoServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderItemService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderOperateHistoryService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderReturnApplyService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderReturnReasonService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OrderSettingService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PaymentInfoService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- RefundInfoService.java -- 
|   |   |   |   |   |   |   +- test -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- order -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallOrderApplicationTests.java -- 
|   |   |   |   |   +- gulimall-product -- 
|   |   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   +- main -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- product -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- config -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MyBatisConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrAttrgroupRelationController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrGroupController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- BrandController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CategoryBrandRelationController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CategoryController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CommentReplayController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ProductAttrValueController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuImagesController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuInfoController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuSaleAttrValueController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuCommentController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuImagesController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuInfoController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuInfoDescController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- dao -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrAttrgroupRelationDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrGroupDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- BrandDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CategoryBrandRelationDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CategoryDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CommentReplayDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ProductAttrValueDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuImagesDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuInfoDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuSaleAttrValueDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuCommentDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuImagesDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuInfoDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuInfoDescDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- entity -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrAttrgroupRelationEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrGroupEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- BrandEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CategoryBrandRelationEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CategoryEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CommentReplayEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ProductAttrValueEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuImagesEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuInfoEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuSaleAttrValueEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuCommentEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuImagesEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuInfoDescEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuInfoEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- exception -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallExceptionControllerAdvice.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- feign -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CouponFeignService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallProductApplication.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrAttrgroupRelationService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrGroupService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- BrandService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CategoryBrandRelationService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CategoryService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CommentReplayService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- impl -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrAttrgroupRelationServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrGroupServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- BrandServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CategoryBrandRelationServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CategoryServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CommentReplayServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ProductAttrValueServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuImagesServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuInfoServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuSaleAttrValueServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuCommentServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuImagesServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuInfoDescServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuInfoServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ProductAttrValueService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuImagesService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuInfoService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SkuSaleAttrValueService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuCommentService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuImagesService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuInfoDescService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuInfoService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- vo -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- Attr.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrGroupRelationVo.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrGroupWithAttrsVo.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrRespVo.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AttrVo.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- BaseAttrs.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- Bounds.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- BrandVo.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- Images.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MemberPrice.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- Skus.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SpuSaveVo.java -- 
|   |   |   |   |   |   |   +- test -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- product -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallProductApplicationTests.java -- 
|   |   |   |   |   +- gulimall-third-party -- 
|   |   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   +- main -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- thirdparty -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OssController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallThirdPartyApplication.java -- 
|   |   |   |   |   |   |   +- test -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- thirdparty -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallThirdPartyApplicationTests.java -- 
|   |   |   |   |   +- gulimall-ware -- 
|   |   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   +- main -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- ware -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- config -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareMyBatisConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseDetailController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareInfoController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareOrderTaskController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareOrderTaskDetailController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareSkuController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- dao -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseDetailDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareInfoDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareOrderTaskDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareOrderTaskDetailDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareSkuDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- entity -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseDetailEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareInfoEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareOrderTaskDetailEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareOrderTaskEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareSkuEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- feign -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ProductFeignService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallWareApplication.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- impl -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseDetailServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareInfoServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareOrderTaskDetailServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareOrderTaskServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareSkuServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseDetailService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareInfoService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareOrderTaskDetailService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareOrderTaskService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WareSkuService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- vo -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- MergeVo.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseDoneVo.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PurchaseItemDoneVo.java -- 
|   |   |   |   |   |   |   +- test -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- com -- 
|   |   |   |   |   |   |   |   |   |   +- atguigu -- 
|   |   |   |   |   |   |   |   |   |   |   +- gulimall -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- ware -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- GulimallWareApplicationTests.java -- 
|   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   +- renren-fast -- 
|   |   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   |   +- db -- 
|   |   |   |   |   |   |   +- mysql.sql -- 
|   |   |   |   |   |   |   +- oracle.sql -- 
|   |   |   |   |   |   |   +- postgresql.sql -- 
|   |   |   |   |   |   |   +- sqlserver.sql -- 
|   |   |   |   |   |   +- docker-compose.yml -- 
|   |   |   |   |   |   +- Dockerfile -- 
|   |   |   |   |   |   +- LICENSE -- 
|   |   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   |   +- README.md -- 
|   |   |   |   |   |   +- renren-fast.iml -- 
|   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   +- main -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- io -- 
|   |   |   |   |   |   |   |   |   |   +- renren -- 
|   |   |   |   |   |   |   |   |   |   |   +- common -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- annotation -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- SysLog.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- aspect -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- RedisAspect.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- SysLogAspect.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- exception -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- RRException.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- RRExceptionHandler.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- utils -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- ConfigConstant.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- Constant.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- DateUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- HttpContextUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- IPUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- MapUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- PageUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- Query.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- R.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- RedisKeys.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- RedisUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- ShiroUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- SpringContextUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- validator -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- Assert.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- group -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AddGroup.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AliyunGroup.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- Group.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- QcloudGroup.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- QiniuGroup.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- UpdateGroup.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- ValidatorUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- xss -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- HTMLFilter.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- SQLFilter.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- XssFilter.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- XssHttpServletRequestWrapper.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- config -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- CorsConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- FilterConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- KaptchaConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- MybatisPlusConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- RedisConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- ShiroConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- SwaggerConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- datasource -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- annotation -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- DataSource.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- aspect -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- DataSourceAspect.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- config -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- DynamicContextHolder.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- DynamicDataSource.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- DynamicDataSourceConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- DynamicDataSourceFactory.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- properties -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- DataSourceProperties.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- DynamicDataSourceProperties.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- modules -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- app -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- annotation -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- Login.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- LoginUser.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- config -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- WebMvcConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AppLoginController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AppRegisterController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AppTestController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- dao -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- UserDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- entity -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- UserEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- form -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- LoginForm.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- RegisterForm.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- interceptor -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AuthorizationInterceptor.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- resolver -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- LoginUserHandlerMethodArgumentResolver.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- impl -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- UserServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- UserService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- utils -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- JwtUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- job -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- config -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJobController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJobLogController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- dao -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJobDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJobLogDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- entity -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJobEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJobLogEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- impl -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJobLogServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJobServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJobLogService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJobService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- task -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ITask.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- TestTask.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- utils -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleJob.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ScheduleUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- oss -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- cloud -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AliyunCloudStorageService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CloudStorageConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- CloudStorageService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OSSFactory.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- QcloudCloudStorageService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- QiniuCloudStorageService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysOssController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- dao -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysOssDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- entity -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysOssEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- impl -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysOssServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysOssService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- sys -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- AbstractController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysConfigController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysLogController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysLoginController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysMenuController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysRoleController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserController.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- dao -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysCaptchaDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysConfigDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysLogDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysMenuDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysRoleDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysRoleMenuDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserRoleDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserTokenDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- entity -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysCaptchaEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysConfigEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysLogEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysMenuEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysRoleEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysRoleMenuEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserRoleEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserTokenEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- form -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- PasswordForm.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysLoginForm.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- oauth2 -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OAuth2Filter.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OAuth2Realm.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- OAuth2Token.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- TokenGenerator.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- redis -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysConfigRedis.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- impl -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ShiroServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysCaptchaServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysConfigServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysLogServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysMenuServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysRoleMenuServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysRoleServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserRoleServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserTokenServiceImpl.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- ShiroService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysCaptchaService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysConfigService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysLogService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysMenuService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysRoleMenuService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysRoleService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserRoleService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserService.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   |   |   +- SysUserTokenService.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- RenrenApplication.java -- 
|   |   |   |   |   |   |   +- test -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- io -- 
|   |   |   |   |   |   |   |   |   |   +- renren -- 
|   |   |   |   |   |   |   |   |   |   |   +- DynamicDataSourceTest.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- JwtTest.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- RedisTest.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- DynamicDataSourceTestService.java -- 
|   |   |   |   |   +- renren-generator -- 
|   |   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   |   +- LICENSE -- 
|   |   |   |   |   |   +- pom.xml -- 
|   |   |   |   |   |   +- README.md -- 
|   |   |   |   |   |   +- renren-generator.iml -- 
|   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   +- main -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- io -- 
|   |   |   |   |   |   |   |   |   |   +- renren -- 
|   |   |   |   |   |   |   |   |   |   |   +- config -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- DbConfig.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- controller -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- SysGeneratorController.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- dao -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- GeneratorDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- MySQLGeneratorDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- OracleGeneratorDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- PostgreSQLGeneratorDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- SQLServerGeneratorDao.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- entity -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- ColumnEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- TableEntity.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- RenrenApplication.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- service -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- SysGeneratorService.java -- 
|   |   |   |   |   |   |   |   |   |   |   +- utils -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- Constant.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- DateUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- GenUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- PageUtils.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- Query.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- R.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- RRException.java -- 
|   |   |   |   |   |   |   |   |   |   |   |   +- RRExceptionHandler.java -- 
|   |   |   |   |   |   |   +- test -- 
|   |   |   |   |   |   |   |   +- java -- 
|   |   |   |   |   |   |   |   |   +- io -- 
|   |   |   |   |   |   |   |   |   |   +- renren -- 
|   |   |   |   |   |   |   |   |   |   |   +- RenrenApplicationTests.java -- 
|   |   |   |   +- sql -- 
|   |   |   |   |   +- gulimall_oms.sql -- 
|   |   |   |   |   +- gulimall_pms.sql -- 
|   |   |   |   |   +- gulimall_sms.sql -- 
|   |   |   |   |   +- gulimall_ums.sql -- 
|   |   |   |   |   +- gulimall_wms.sql -- 
|   |   |   |   |   +- pms_catelog.sql -- 
|   |   |   |   |   +- sys_menus.sql -- 
|   |   |   |   |   +- 资料源码 - 快捷方式.lnk -- 
|   |   |   |   +- 前端 -- 
|   |   |   |   |   +- es6 -- 
|   |   |   |   |   |   +- 1、let.html -- 
|   |   |   |   |   |   +- 2、解构表达式.html -- 
|   |   |   |   |   |   +- 3、函数优化.html -- 
|   |   |   |   |   |   +- 4、对象优化.html -- 
|   |   |   |   |   |   +- 5、map和reduce.html -- 
|   |   |   |   |   |   +- 6、promise.html -- 
|   |   |   |   |   |   +- 7、模块化.html -- 
|   |   |   |   |   |   +- js -- 
|   |   |   |   |   |   |   +- hello.js -- 
|   |   |   |   |   |   |   +- main.js -- 
|   |   |   |   |   |   |   +- user.js -- 
|   |   |   |   |   |   +- mock -- 
|   |   |   |   |   |   |   +- corse_score_10.json -- 
|   |   |   |   |   |   |   +- user.json -- 
|   |   |   |   |   |   |   +- user_corse_1.json -- 
|   |   |   |   |   +- gulimall-admin-vue（完整代码）.zip -- 
|   |   |   |   |   +- modules -- 
|   |   |   |   |   |   +- common -- 
|   |   |   |   |   |   |   +- brand-select.vue -- 
|   |   |   |   |   |   |   +- category-cascader.vue -- 
|   |   |   |   |   |   |   +- category.vue -- 
|   |   |   |   |   |   +- coupon -- 
|   |   |   |   |   |   |   +- bounds.vue -- 
|   |   |   |   |   |   |   +- coupon-add-or-update.vue -- 
|   |   |   |   |   |   |   +- coupon.vue -- 
|   |   |   |   |   |   |   +- couponspucategoryrelation-add-or-update.vue -- 
|   |   |   |   |   |   |   +- couponspucategoryrelation.vue -- 
|   |   |   |   |   |   |   +- couponspurelation-add-or-update.vue -- 
|   |   |   |   |   |   |   +- couponspurelation.vue -- 
|   |   |   |   |   |   |   +- full.vue -- 
|   |   |   |   |   |   |   +- history.vue -- 
|   |   |   |   |   |   |   +- homeadv-add-or-update.vue -- 
|   |   |   |   |   |   |   +- homeadv.vue -- 
|   |   |   |   |   |   |   +- homesubject-add-or-update.vue -- 
|   |   |   |   |   |   |   +- homesubjectspu-add-or-update.vue -- 
|   |   |   |   |   |   |   +- homesubjectspu.vue -- 
|   |   |   |   |   |   |   +- memberprice-add-or-update.vue -- 
|   |   |   |   |   |   |   +- memberprice.vue -- 
|   |   |   |   |   |   |   +- seckill.vue -- 
|   |   |   |   |   |   |   +- seckillpromotion-add-or-update.vue -- 
|   |   |   |   |   |   |   +- seckillsession-add-or-update.vue -- 
|   |   |   |   |   |   |   +- seckillsession.vue -- 
|   |   |   |   |   |   |   +- seckillskunotice-add-or-update.vue -- 
|   |   |   |   |   |   |   +- seckillskunotice.vue -- 
|   |   |   |   |   |   |   +- seckillskurelation-add-or-update.vue -- 
|   |   |   |   |   |   |   +- seckillskurelation.vue -- 
|   |   |   |   |   |   |   +- skufullreduction-add-or-update.vue -- 
|   |   |   |   |   |   |   +- skuladder-add-or-update.vue -- 
|   |   |   |   |   |   |   +- skuladder.vue -- 
|   |   |   |   |   |   |   +- spubounds-add-or-update.vue -- 
|   |   |   |   |   |   |   +- subject.vue -- 
|   |   |   |   |   |   +- job -- 
|   |   |   |   |   |   |   +- schedule-add-or-update.vue -- 
|   |   |   |   |   |   |   +- schedule-log.vue -- 
|   |   |   |   |   |   |   +- schedule.vue -- 
|   |   |   |   |   |   +- member -- 
|   |   |   |   |   |   |   +- level.vue -- 
|   |   |   |   |   |   |   +- member-add-or-update.vue -- 
|   |   |   |   |   |   |   +- member.vue -- 
|   |   |   |   |   |   |   +- memberlevel-add-or-update.vue -- 
|   |   |   |   |   |   +- order -- 
|   |   |   |   |   |   |   +- order-add-or-update.vue -- 
|   |   |   |   |   |   |   +- order.vue -- 
|   |   |   |   |   |   |   +- orderitem-add-or-update.vue -- 
|   |   |   |   |   |   |   +- orderitem.vue -- 
|   |   |   |   |   |   |   +- orderoperatehistory-add-or-update.vue -- 
|   |   |   |   |   |   |   +- orderoperatehistory.vue -- 
|   |   |   |   |   |   |   +- orderreturnapply-add-or-update.vue -- 
|   |   |   |   |   |   |   +- orderreturnreason-add-or-update.vue -- 
|   |   |   |   |   |   |   +- orderreturnreason.vue -- 
|   |   |   |   |   |   |   +- ordersetting-add-or-update.vue -- 
|   |   |   |   |   |   |   +- payment.vue -- 
|   |   |   |   |   |   |   +- paymentinfo-add-or-update.vue -- 
|   |   |   |   |   |   |   +- refund.vue -- 
|   |   |   |   |   |   |   +- refundinfo-add-or-update.vue -- 
|   |   |   |   |   |   |   +- return.vue -- 
|   |   |   |   |   |   |   +- settings.vue -- 
|   |   |   |   |   |   +- oss -- 
|   |   |   |   |   |   |   +- oss-config.vue -- 
|   |   |   |   |   |   |   +- oss-upload.vue -- 
|   |   |   |   |   |   |   +- oss.vue -- 
|   |   |   |   |   |   +- product -- 
|   |   |   |   |   |   |   +- attr-add-or-update.vue -- 
|   |   |   |   |   |   |   +- attr-group-relation.vue -- 
|   |   |   |   |   |   |   +- attrgroup-add-or-update.vue -- 
|   |   |   |   |   |   |   +- attrgroup.vue -- 
|   |   |   |   |   |   |   +- attrupdate.vue -- 
|   |   |   |   |   |   |   +- baseattr.vue -- 
|   |   |   |   |   |   |   +- brand-add-or-update.vue -- 
|   |   |   |   |   |   |   +- brand.vue -- 
|   |   |   |   |   |   |   +- category.vue -- 
|   |   |   |   |   |   |   +- manager.vue -- 
|   |   |   |   |   |   |   +- saleattr.vue -- 
|   |   |   |   |   |   |   +- spu.vue -- 
|   |   |   |   |   |   |   +- spuadd.vue -- 
|   |   |   |   |   |   |   +- spuinfo.vue -- 
|   |   |   |   |   |   +- sys -- 
|   |   |   |   |   |   |   +- config-add-or-update.vue -- 
|   |   |   |   |   |   |   +- config.vue -- 
|   |   |   |   |   |   |   +- log.vue -- 
|   |   |   |   |   |   |   +- menu-add-or-update.vue -- 
|   |   |   |   |   |   |   +- menu.vue -- 
|   |   |   |   |   |   |   +- role-add-or-update.vue -- 
|   |   |   |   |   |   |   +- role.vue -- 
|   |   |   |   |   |   |   +- user-add-or-update.vue -- 
|   |   |   |   |   |   |   +- user.vue -- 
|   |   |   |   |   |   +- ware -- 
|   |   |   |   |   |   |   +- purchase-add-or-update.vue -- 
|   |   |   |   |   |   |   +- purchase.vue -- 
|   |   |   |   |   |   |   +- purchasedetail-add-or-update.vue -- 
|   |   |   |   |   |   |   +- purchaseitem.vue -- 
|   |   |   |   |   |   |   +- sku.vue -- 
|   |   |   |   |   |   |   +- task.vue -- 
|   |   |   |   |   |   |   +- wareinfo-add-or-update.vue -- 
|   |   |   |   |   |   |   +- wareinfo.vue -- 
|   |   |   |   |   |   |   +- wareordertask-add-or-update.vue -- 
|   |   |   |   |   |   |   +- wareordertaskdetail-add-or-update.vue -- 
|   |   |   |   |   |   |   +- wareordertaskdetail.vue -- 
|   |   |   |   |   |   |   +- waresku-add-or-update.vue -- 
|   |   |   |   |   +- upload -- 
|   |   |   |   |   |   +- multiUpload.vue -- 
|   |   |   |   |   |   +- policy.js -- 
|   |   |   |   |   |   +- singleUpload.vue -- 
|   |   |   |   |   +- vue-demo -- 
|   |   |   |   |   |   +- vue-demo -- 
|   |   |   |   |   |   |   +- .babelrc -- 
|   |   |   |   |   |   |   +- .editorconfig -- 
|   |   |   |   |   |   |   +- .gitignore -- 
|   |   |   |   |   |   |   +- .postcssrc.js -- 
|   |   |   |   |   |   |   +- build -- 
|   |   |   |   |   |   |   |   +- build.js -- 
|   |   |   |   |   |   |   |   +- check-versions.js -- 
|   |   |   |   |   |   |   |   +- logo.png -- 
|   |   |   |   |   |   |   |   +- utils.js -- 
|   |   |   |   |   |   |   |   +- vue-loader.conf.js -- 
|   |   |   |   |   |   |   |   +- webpack.base.conf.js -- 
|   |   |   |   |   |   |   |   +- webpack.dev.conf.js -- 
|   |   |   |   |   |   |   |   +- webpack.prod.conf.js -- 
|   |   |   |   |   |   |   +- config -- 
|   |   |   |   |   |   |   |   +- dev.env.js -- 
|   |   |   |   |   |   |   |   +- index.js -- 
|   |   |   |   |   |   |   |   +- prod.env.js -- 
|   |   |   |   |   |   |   +- index.html -- 
|   |   |   |   |   |   |   +- package-lock.json -- 
|   |   |   |   |   |   |   +- package.json -- 
|   |   |   |   |   |   |   +- README.md -- 
|   |   |   |   |   |   |   +- src -- 
|   |   |   |   |   |   |   |   +- App.vue -- 
|   |   |   |   |   |   |   |   +- assets -- 
|   |   |   |   |   |   |   |   |   +- logo.png -- 
|   |   |   |   |   |   |   |   +- components -- 
|   |   |   |   |   |   |   |   |   +- Hello.vue -- 
|   |   |   |   |   |   |   |   |   +- HelloWorld.vue -- 
|   |   |   |   |   |   |   |   |   +- MyTable.vue -- 
|   |   |   |   |   |   |   |   +- main.js -- 
|   |   |   |   |   |   |   |   +- router -- 
|   |   |   |   |   |   |   |   |   +- index.js -- 
|   |   |   |   |   |   |   +- static -- 
|   |   |   |   |   |   |   |   +- .gitkeep -- 
|   |   |   |   |   +- vue2 -- 
|   |   |   |   |   |   +- 1、指令 -- 
|   |   |   |   |   |   |   +- 1、v-text、v-html.html -- 
|   |   |   |   |   |   |   +- 2、v-bind.html -- 
|   |   |   |   |   |   |   +- 3、v-model.html -- 
|   |   |   |   |   |   |   +- 4、v-on.html -- 
|   |   |   |   |   |   |   +- 5、v-for.html -- 
|   |   |   |   |   |   |   +- 6、v-if和v-show.html -- 
|   |   |   |   |   |   |   +- 7、v-else和v-else-if.html -- 
|   |   |   |   |   |   +- 2、计算属性和侦听器 -- 
|   |   |   |   |   |   |   +- 1、计算属性和侦听器.html -- 
|   |   |   |   |   |   |   +- 2、过滤器.html -- 
|   |   |   |   |   |   +- 3、组件化 -- 
|   |   |   |   |   |   |   +- 1、组件化.html -- 
|   |   |   |   |   |   +- 4、生命周期钩子函数 -- 
|   |   |   |   |   |   |   +- 1、生命周期.html -- 
|   |   |   |   |   |   +- index.html -- 
|   |   |   |   |   |   +- package-lock.json -- 
|   |   |   |   |   |   +- package.json -- 
|   |   |   +- 谷粒商城-分布式基础-图.pdf -- 
|   |   |   +- 谷粒商城-微服务架构图.jpg -- 
|   |   +- 代码 -- 
|   |   |   +- enume -- 
|   |   |   |   +- OrderStatusEnum.java -- 
|   |   |   +- html -- 
|   |   |   |   +- 分类 -- 
|   |   |   |   |   +- bootstrap -- 
|   |   |   |   |   |   +- css -- 
|   |   |   |   |   |   |   +- bootstrap.css -- 
|   |   |   |   |   |   |   +- bootstrap.min.css -- 
|   |   |   |   |   |   +- js -- 
|   |   |   |   |   |   |   +- bootstrap.js -- 
|   |   |   |   |   |   |   +- bootstrap.min.js -- 
|   |   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   +- css -- 
|   |   |   |   |   |   +- index.css -- 
|   |   |   |   |   |   +- index.css.map -- 
|   |   |   |   |   |   +- index.scss -- 
|   |   |   |   |   |   +- swiper.min.css -- 
|   |   |   |   |   +- index.html -- 
|   |   |   |   |   +- js -- 
|   |   |   |   |   |   +- index.js -- 
|   |   |   |   |   |   +- jquery-3.1.1.js -- 
|   |   |   |   |   |   +- swiper.min.js -- 
|   |   |   |   +- 搜索页 -- 
|   |   |   |   |   +- css -- 
|   |   |   |   |   |   +- index.css -- 
|   |   |   |   |   |   +- index.css.map -- 
|   |   |   |   |   +- font -- 
|   |   |   |   |   |   +- demo.css -- 
|   |   |   |   |   |   +- demo_fontclass.html -- 
|   |   |   |   |   |   +- demo_symbol.html -- 
|   |   |   |   |   |   +- demo_unicode.html -- 
|   |   |   |   |   |   +- iconfont.css -- 
|   |   |   |   |   |   +- iconfont.eot -- 
|   |   |   |   |   |   +- iconfont.js -- 
|   |   |   |   |   |   +- iconfont.svg -- 
|   |   |   |   |   |   +- iconfont.ttf -- 
|   |   |   |   |   |   +- iconfont.woff -- 
|   |   |   |   |   +- index.html -- 
|   |   |   |   |   +- js -- 
|   |   |   |   |   |   +- jquery-1.12.4.js -- 
|   |   |   |   |   |   +- jquery-3.2.1.min.js -- 
|   |   |   |   |   +- sass -- 
|   |   |   |   |   |   +- index.scss -- 
|   |   |   |   +- 收银页 -- 
|   |   |   |   |   +- css -- 
|   |   |   |   |   |   +- style.css -- 
|   |   |   |   |   +- index.html -- 
|   |   |   |   |   +- js -- 
|   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   +- 注册页面 -- 
|   |   |   |   |   +- bootStrap -- 
|   |   |   |   |   |   +- bootstrap -- 
|   |   |   |   |   |   |   +- css -- 
|   |   |   |   |   |   |   |   +- bootstrap.css -- 
|   |   |   |   |   |   |   |   +- bootstrap.min.css -- 
|   |   |   |   |   |   |   +- js -- 
|   |   |   |   |   |   |   |   +- bootstrap.js -- 
|   |   |   |   |   |   |   |   +- bootstrap.min.js -- 
|   |   |   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   +- css -- 
|   |   |   |   |   |   +- index.css -- 
|   |   |   |   |   +- index.html -- 
|   |   |   |   |   +- js -- 
|   |   |   |   |   |   +- easyUI -- 
|   |   |   |   |   |   |   +- AUTHORS.txt -- 
|   |   |   |   |   |   |   +- external -- 
|   |   |   |   |   |   |   |   +- jquery -- 
|   |   |   |   |   |   |   |   |   +- jquery.js -- 
|   |   |   |   |   |   |   +- index.html -- 
|   |   |   |   |   |   |   +- jquery-ui.css -- 
|   |   |   |   |   |   |   +- jquery-ui.js -- 
|   |   |   |   |   |   |   +- jquery-ui.min.css -- 
|   |   |   |   |   |   |   +- jquery-ui.min.js -- 
|   |   |   |   |   |   |   +- jquery-ui.structure.css -- 
|   |   |   |   |   |   |   +- jquery-ui.structure.min.css -- 
|   |   |   |   |   |   |   +- jquery-ui.theme.css -- 
|   |   |   |   |   |   |   +- jquery-ui.theme.min.css -- 
|   |   |   |   |   |   |   +- LICENSE.txt -- 
|   |   |   |   |   |   |   +- package.json -- 
|   |   |   |   |   |   +- index.js -- 
|   |   |   |   |   |   +- jQuery -- 
|   |   |   |   |   |   |   +- jquery-1.11.1.js -- 
|   |   |   |   |   |   |   +- jquery-1.7.2.js -- 
|   |   |   |   |   |   |   +- jquery-1.8.3.js -- 
|   |   |   |   |   |   |   +- jquery-1.9.1.js -- 
|   |   |   |   |   |   |   +- jquery-3.1.1.js -- 
|   |   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   |   |   +- jquery-3.2.1.slim.min.js -- 
|   |   |   |   |   |   |   +- jquery.form.js -- 
|   |   |   |   |   |   |   +- jquery.js -- 
|   |   |   |   |   |   |   +- jquery.mockjax-1.5.3.js -- 
|   |   |   |   |   |   |   +- jquery.mockjax-2.2.1.js -- 
|   |   |   |   |   |   |   +- jquery.mockjax.js -- 
|   |   |   |   |   |   |   +- jquery.simulate.js -- 
|   |   |   |   |   |   |   +- require.js -- 
|   |   |   |   |   +- libs -- 
|   |   |   |   |   |   +- jquery-1.12.4.min.js -- 
|   |   |   |   |   +- sass -- 
|   |   |   |   |   |   +- index.css -- 
|   |   |   |   |   |   +- index.css.map -- 
|   |   |   |   |   |   +- index.scss -- 
|   |   |   |   +- 登录页面 -- 
|   |   |   |   |   +- index.html -- 
|   |   |   |   |   +- JD_js -- 
|   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   |   +- zepto.js -- 
|   |   |   |   |   +- JD_sass -- 
|   |   |   |   |   |   +- JD1.css -- 
|   |   |   |   |   |   +- JD1.css.map -- 
|   |   |   |   |   |   +- JD1.scss -- 
|   |   |   |   +- 等待付款 -- 
|   |   |   |   |   +- bootstrap -- 
|   |   |   |   |   |   +- css -- 
|   |   |   |   |   |   |   +- bootstrap.css -- 
|   |   |   |   |   |   |   +- bootstrap.min.css -- 
|   |   |   |   |   |   +- js -- 
|   |   |   |   |   |   |   +- bootstrap.js -- 
|   |   |   |   |   |   |   +- bootstrap.min.js -- 
|   |   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   +- css -- 
|   |   |   |   |   |   +- scss.css -- 
|   |   |   |   |   |   +- scss.css.map -- 
|   |   |   |   |   |   +- scss.scss -- 
|   |   |   |   |   |   +- swiper.css -- 
|   |   |   |   |   +- index.html -- 
|   |   |   |   |   +- js -- 
|   |   |   |   |   |   +- index.js -- 
|   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   |   +- lunbo.js -- 
|   |   |   |   |   |   +- swiper.js -- 
|   |   |   |   |   |   +- zepto.min.js -- 
|   |   |   |   |   +- swiper -- 
|   |   |   |   |   |   +- swiper-3.4.2.jquery.min.js -- 
|   |   |   |   |   |   +- swiper-3.4.2.min.css -- 
|   |   |   |   |   |   +- swiper-3.4.2.min.js -- 
|   |   |   |   +- 结算页 -- 
|   |   |   |   |   +- css -- 
|   |   |   |   |   |   +- index.css -- 
|   |   |   |   |   |   +- index.scss -- 
|   |   |   |   |   |   +- JD2.css -- 
|   |   |   |   |   |   +- JD2.css.map -- 
|   |   |   |   |   |   +- JD2.scss -- 
|   |   |   |   |   +- index.html -- 
|   |   |   |   |   +- js -- 
|   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   +- sass -- 
|   |   |   |   |   |   +- JD2.scss -- 
|   |   |   |   +- 订单页 -- 
|   |   |   |   |   +- css -- 
|   |   |   |   |   |   +- index.css -- 
|   |   |   |   |   |   +- index.css.map -- 
|   |   |   |   |   +- index.html -- 
|   |   |   |   |   +- js -- 
|   |   |   |   |   |   +- index.js -- 
|   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   +- sass -- 
|   |   |   |   |   |   +- index.scss -- 
|   |   |   |   +- 详情页 -- 
|   |   |   |   |   +- bootstrap -- 
|   |   |   |   |   |   +- css -- 
|   |   |   |   |   |   |   +- bootstrap.css -- 
|   |   |   |   |   |   |   +- bootstrap.min.css -- 
|   |   |   |   |   |   +- js -- 
|   |   |   |   |   |   |   +- bootstrap.js -- 
|   |   |   |   |   |   |   +- bootstrap.min.js -- 
|   |   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   +- item.html -- 
|   |   |   |   |   +- js -- 
|   |   |   |   |   |   +- index.js -- 
|   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   |   +- jquery1.9.js -- 
|   |   |   |   |   |   +- js.js -- 
|   |   |   |   |   +- scss -- 
|   |   |   |   |   |   +- header.css -- 
|   |   |   |   |   |   +- main.css -- 
|   |   |   |   |   |   +- shop.css -- 
|   |   |   |   |   |   +- SHOUhou.css -- 
|   |   |   |   |   +- shangpinxiangqing.html -- 
|   |   |   |   +- 购物车 -- 
|   |   |   |   |   +- bootstrap -- 
|   |   |   |   |   |   +- css -- 
|   |   |   |   |   |   |   +- bootstrap.css -- 
|   |   |   |   |   |   |   +- bootstrap.min.css -- 
|   |   |   |   |   |   +- js -- 
|   |   |   |   |   |   |   +- bootstrap.js -- 
|   |   |   |   |   |   |   +- bootstrap.min.js -- 
|   |   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   +- cartList.html -- 
|   |   |   |   |   +- css -- 
|   |   |   |   |   |   +- font-awesome-4.7.0 -- 
|   |   |   |   |   |   |   +- css -- 
|   |   |   |   |   |   |   |   +- font-awesome.css -- 
|   |   |   |   |   |   |   |   +- font-awesome.min.css -- 
|   |   |   |   |   |   |   +- HELP-US-OUT.txt -- 
|   |   |   |   |   |   |   +- less -- 
|   |   |   |   |   |   |   |   +- animated.less -- 
|   |   |   |   |   |   |   |   +- bordered-pulled.less -- 
|   |   |   |   |   |   |   |   +- core.less -- 
|   |   |   |   |   |   |   |   +- fixed-width.less -- 
|   |   |   |   |   |   |   |   +- font-awesome.less -- 
|   |   |   |   |   |   |   |   +- icons.less -- 
|   |   |   |   |   |   |   |   +- larger.less -- 
|   |   |   |   |   |   |   |   +- list.less -- 
|   |   |   |   |   |   |   |   +- mixins.less -- 
|   |   |   |   |   |   |   |   +- path.less -- 
|   |   |   |   |   |   |   |   +- rotated-flipped.less -- 
|   |   |   |   |   |   |   |   +- screen-reader.less -- 
|   |   |   |   |   |   |   |   +- stacked.less -- 
|   |   |   |   |   |   |   |   +- variables.less -- 
|   |   |   |   |   |   |   +- scss -- 
|   |   |   |   |   |   |   |   +- font-awesome.scss -- 
|   |   |   |   |   |   |   |   +- _animated.scss -- 
|   |   |   |   |   |   |   |   +- _bordered-pulled.scss -- 
|   |   |   |   |   |   |   |   +- _core.scss -- 
|   |   |   |   |   |   |   |   +- _fixed-width.scss -- 
|   |   |   |   |   |   |   |   +- _icons.scss -- 
|   |   |   |   |   |   |   |   +- _larger.scss -- 
|   |   |   |   |   |   |   |   +- _list.scss -- 
|   |   |   |   |   |   |   |   +- _mixins.scss -- 
|   |   |   |   |   |   |   |   +- _path.scss -- 
|   |   |   |   |   |   |   |   +- _rotated-flipped.scss -- 
|   |   |   |   |   |   |   |   +- _screen-reader.scss -- 
|   |   |   |   |   |   |   |   +- _stacked.scss -- 
|   |   |   |   |   |   |   |   +- _variables.scss -- 
|   |   |   |   |   |   +- index.css -- 
|   |   |   |   |   |   +- One_bdyStyle.css -- 
|   |   |   |   |   |   +- One_mainFoot.css -- 
|   |   |   |   |   |   +- success.css -- 
|   |   |   |   |   |   +- swiper.min.css -- 
|   |   |   |   |   +- js -- 
|   |   |   |   |   |   +- index.js -- 
|   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   |   +- success.js -- 
|   |   |   |   |   |   +- swiper.min.js -- 
|   |   |   |   |   +- success.html -- 
|   |   |   |   +- 首页资源 -- 
|   |   |   |   |   +- index -- 
|   |   |   |   |   |   +- css -- 
|   |   |   |   |   |   |   +- GL.css -- 
|   |   |   |   |   |   |   +- swiper-3.4.2.min.css -- 
|   |   |   |   |   |   +- js -- 
|   |   |   |   |   |   |   +- catalogLoader.js -- 
|   |   |   |   |   |   |   +- header.js -- 
|   |   |   |   |   |   |   +- index.js -- 
|   |   |   |   |   |   |   +- jquery-3.1.1.min.js -- 
|   |   |   |   |   |   |   +- left,top.js -- 
|   |   |   |   |   |   |   +- secend.js -- 
|   |   |   |   |   |   |   +- swiper-3.4.2.jquery.min.js -- 
|   |   |   |   |   |   |   +- swiper-3.4.2.min.js -- 
|   |   |   |   |   |   |   +- text.js -- 
|   |   |   |   |   |   |   +- zz.js -- 
|   |   |   |   |   |   +- json -- 
|   |   |   |   |   |   |   +- catalog.json -- 
|   |   |   |   |   +- index.html -- 
|   |   |   +- 支付 -- 
|   |   |   |   +- AlipayTemplate.java -- 
|   |   |   |   +- application.properties -- 
|   |   |   |   +- PayAsyncVo.java -- 
|   |   |   |   +- PayVo.java -- 
|   |   +- 谷粒商城-分布式高级-图.pdf -- 
|   |   +- 谷粒商城-微服务架构图.jpg -- 
|   +- 资料源码下载地址.txt -- 
|   +- 软件.docx -- 
|   +- 软件.zip -- 
```

#### 后端技术栈

| 技术                             | 版本            | 说明                          |
|--------------------------------|---------------|-----------------------------|
| 示例: Spring Boot Starter Parent | 2.0.4.RELEASE | Spring Boot 父依赖             |

#### 前端技术栈

| 技术       | 版本         | 说明                                       |
|----------|------------|------------------------------------------|
| 示例：axios | ^0.16.2    | HTTP请求库                                  |


#### 安装教程


#### 登录账户

#### 截图

#### 拓展知识
