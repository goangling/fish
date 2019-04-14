从零到一: 从想法到上线
---

# 1.idea
爱好钓鱼，想搞个社群，并以此为生。找了一下，类似的还不少，飞鱼行、百姓钓鱼论坛等，这玩意应该叫社群电商。
## 可能实现方式
- SaaS
比如微商、淘宝、有赞，功能模块化、服务器在云端，可以快速搭建使用； 几乎没有运营需求定制功能而且数据都在saas厂商手里。

- 开源模版+二次开发模式
前期使用成本比较低，而且程序开源随时可以根据需求定制，费用分阶段投入，更适合从小做到大的公司发展过程；前期需要很好的对电商平台进行功能规划，否则后期项目结构混乱，阅读性和可维护性会大大降低。

- 定制模式
最大程度的设计好前期的构架，打造出符合企业发展模式的电商平台；开发周期长，成本高，一般只有大型企业才会考虑这种模式。

基于以上考虑，以及技术团队、开发商城系统的经验、开发周期和成本[1](https://www.sohu.com/a/133311333_476636)，寻找社交、商城相关公司的成型产品源码，自己二次开发。
这个要注意出售方自己也做该行业，比如上海零亦就是类似平台，后来做了飞鱼行。   
# 2.需求梳理、分析
- 产品功能脑图
- 功能列表

# 3 .选型
### 对方公司综合实力
公司年龄、公司规模、公司产品线、公司员工专业度
### 自己公司定位
未来发展方向已确定，确定源码、开发语言、产品等级等作为过滤条件
### 综合评估产品功能符合度、质量、价格
## 3.1 优先查询社交网络服务SNS：
- 知名开源SNS系统    
OpenSNS，基于ThinkPHP框架是国内第一，
社区活跃度，产品成熟度，程序的扩展性，
- thinksns    
演示、网站更友好，新的是ThinkSNS+，使用的Laravel框架是国际第一
- 近乎 asp.net， 不行 
- 其他小众大多PHP，发展的不行
- Java
TLP社交网络服务系统（前台+后台）源码（SrpingBoot+Jsp+MySQL）

`需要需求梳理完毕、向2家SNS咨询报价1~3年的报价。`
购买需要的支持
技术支持：需求梳理、系统架构设计、UI、软件开发、测试、部署实施、软件迭代维护、设备维护
产品支持：行业分析、竞品分析、用户研究、需求分析、功能设计、文案优化、用户体验、
运营支持：用户画像、活动创意

## 端侧
跟随后台，opensns、thinksns都有各自代码。
vue.js 开源方便的迁移到uni-app， 某些模块不支持，比如Vue-router，必须用uni-app的，需要分析使用了哪些模块，有一定工作量。还要看体验能否跟上自带的app。

## 3.2 再查询社群电商
这有一堆的，比如[港湾有巣](http://www.lnest.com/zhongchou/)等等



# 4. 开发
这些都依赖采购的源码
## 4.1产品原型图绘制
- 全局流图
- 业务流程的泳道图
- 墨刀做交互原型

## 4.2 UI设计
- 风格稿
- 内页设计
- 切图、标注

## 4.3细化需求

## 4.4 技术方案 & 架构设计
- 服务器架构
- APP架构
![](http://img.mp.itc.cn/upload/20160730/3602181d3d5e4302ad7d869fcd4afeb6_th.png)

## 4.5 项目排期 & 任务分解
## 4.6 产品研发阶段
## 4.7 测试阶段
## 4.8 部署上线
公有云选择：

- 阿里云：  
整体优势突出，可持续，可预期，稳定性有保障的产品，贵点、超卖
- 华为云：  
关系不错， 跑分优先。

部署形态： 参考源码方建议

- 虚拟机
- Docker


##  5.维护运营 

