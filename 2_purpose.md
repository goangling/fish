# 2. 架构目标和关键质量属性
## 2.1 架构目标
### 2.1.1 背景说明
我的钓场是品浪公司面向钓鱼社群的一整体IT系统方案的总称，包括云层、端侧，如下图所示。

定制业务： 关注、圈子、精选、商城、用户、钱包
业务中台： 用户管理/后台管理/游客模式/圈子/资讯/直播
技术平台： ECS/OBS/CDN/MySQL/ELB/Redis/监控/日志/WAF

其中技术平台，主要考虑采用稳定可靠的云服务，业务中台主要进行能力封装，定制业务层只需要根据中台提供的能力简单开发迅速完成业务需求。

逻辑架构层如下图：
前端接触层： 交互渠道  Web、H5、Android、iOS       客户、合作伙伴？
服务层：  用户管理
基础设施层：云化：弹性、分布式、并行

### 2.1.2 架构目标
考虑目前市面上的常见社群电商，兼顾未来品浪拓宽需求，架构目标：
1. 月活百万级用户规模。
2. 云化运维、部署升级自动化、平滑升级。
3. 快速开发上线。

## 2.2 架构约束
- SaaS
比如微商、淘宝、有赞，功能模块化、服务器在云端，可以快速搭建使用； 几乎没有运营需求定制功能而且数据都在saas厂商手里。

- 开源模版+二次开发模式
前期使用成本比较低，而且程序开源随时可以根据需求定制，费用分阶段投入，更适合从小做到大的公司发展过程；前期需要很好的对电商平台进行功能规划，否则后期项目结构混乱，阅读性和可维护性会大大降低。

- 定制模式
最大程度的设计好前期的构架，打造出符合企业发展模式的电商平台；开发周期长，成本高，一般只有大型企业才会考虑这种模式。

由于是从零开始，考虑技术团队、开发商城系统的经验、开发周期和成本，建议采购源码进行二次开发。

## 2.3 架构原则
- 云化架构： 直接上云，P层、I层都使用云服务商的。
- 模块化架构：各个模块之间充分解耦
- 分层架构：展示层、领域逻辑层、数据存储层分离，任意一层变化对其他层影响最小化。


