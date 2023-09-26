# 个人简历

#### 介绍

- **姓名**：刘京凯

- **年龄**：29岁

- **学校**：琼州学院三亚校区

- **工作年限**：6年

- **擅长语言**：go,php ,html,css

- **技术栈**：php当前主流框架都可快速上手如`laravel` ,`thinkphp`,`symfony`，`hyperfy` ... ,go语言的`gin`，`go-zero`等框架，mysql`,`redis`,`nginx`,`kafka`,`elasticsearch`,`nats`等开源软件也可以熟练的应用到程序中

- **自我评价**：可以迅速上手go，或者php任何框架，对代码风格有严格要求，拒绝写垃圾代码，需求明确的项目都可以迅速开发

  ------

  

#### 工作经历

### 2019年11月~现在

##### 西安云界网络科技有限公司

**短链接项目:**

项目介绍:一个用于公司内部营销短信和Apppush的短链接服务，包含转链、存储、链接跳转功能，并能提供点击上报数据报功能。支撑了公司内部2条业务线，覆盖了数万用户，从上线至今稳定运行1年。

​    个人职责:

 - 负责项目的整体设计和开发,负责实现转链和链接跳转模块逻辑。
 - 基于MySQL主键实现了高可用的发号器组件。
 - 在转链前进行特殊词过滤和防止循环转链的校验处理。
 - 链接跳转前采用缓存和读写分离的方法降低程序的响应耗时。
 - 与业务系统分开部署，通过EFK采集nginx日志方式统计短链接的点击数据。

**jyinstall项目**

- 技术：go语言,分布式消息中间件nats,存储redis,mysql 
- 项目介绍：这款软件主要是面向站长端的统计工具可以统计app端，和web端的用户d的用户行为，类似openinstall，站长集成jyinstall后可以在后台方便，直观的看到每日pv，uv，ip 新增用户等站长需要看到的数据利于SEO优化
- 项目架构：客户集成sdk后请求接口，接口只做将请求写入nats队列中异步削峰，消费利用go语言天生支持协程的特性使用worker pool进行消费，可以快速消费数据，其中存储统计用到redis多种数据结构如hash（每日增量统计）,set（ip池）,bitmap(新老活跃用户留存统计)



 **有准星**

- 技术：laravel ,hyperf,redis,msql 
- 项目介绍：项目主要是面向喜欢星座的受用群体，是外包日本的一款app，在这个项目中我主要负责，后台管理的开发，和app端接口的开发。主要功能有用户发布动态，评论动态，用户通过占卜星盘，摇一摇在线匹配，漂流瓶，在线匹配出最适合用户的交友系统。
- 项目架构：c端(app端)，api接口用到的框架是php基于swoole扩展的hyperf框架，主要用到了腾讯云im 进行用户im部分的开发，消息推送也是基于腾讯im,队列主要使用hyperf自带的，基于redis实现的消息队列。星盘的匹配主要用了第三方的sdk，其中因为sdk给出的结果是中文，但是交付用户是日本客户，所以用到了穷举法，将返回结果穷举分段翻译。后台主要用到了laravel-admin对用户，动态，进行管理，统计用户性别，年龄等分布比例



**果果社区**

- 技术：laravel ,redis,msql
- 项目介绍：类似于豆瓣类app，用户可以建立自己的小组，发布动态，相互关注，影评，观赏电影
- 项目架构： app端api及后台管理均采用laravel 开发，所有功能均有本人独立开发完成，其中用到了elasticsearch 分词搜索，队列采用laravel自带的队列，所有关系型结构如评论和动态都是采取观察者模式进行触发操作。可在应用市场搜索（片仓或果果社区）

**Kaa云课堂**

- 项目介绍：在线云课堂，使用thinkphp基于腾讯教育sdk进行二次开发，本人在其中担任app接口开发，分为教师端和学生端，教师端可发布课程，发布作业，开课前15分钟可以进入课堂开始备课，在上课期间可以对课堂学员设置身份（助教），可操作上麦，下麦，禁言等操作。学生可以根据课程码加入老师的课程观看直播，可完成老师布置的作业。



#### 2019/3-2019/11  西安有请网络科技有限公司

工作描述：项目采取前后端分离B/S架构，前端vue，app采用uniapp，采用redis消息队列，框架采用thinkphp5.1

项目整体为官网，酒店商家后台，app，小程序，总后台 

1. go语言.数据采集，从各大数据源采集酒店所需数据

2. 负责整体数据库的设计与调优 

3. 后台APP接口开发restful风格

4. 编写接口文档 

5. 负责整体项目后台架构 6.
6. 官网链接 www.yesplease.cn pc 后台链接：shop.yesplease.cn app 可在 appstore 或 应用软件市场搜索 有请宴会管理系统



#### 2018/3-2019/2 西安大易德行网络科技有限公司

**公众号城慧玩**:

- 项目描述：该项采用前端框架weUi,php框架laravel5.1主要 由本人与两名前端一起完成这个项目其中所用到的技术。RESTFUL风格的接口。消息队列，elasticsearch 的 搜索分词，wokerman构建的客服系统。 

- 责任描述：接口文档的编写，数据库设计，与后台的编写

  

**启修哥APP** ：

- 项目描述：与中石油生活网合资生产的APP： 该项目采用thinkphp5,redis,mysql,vue,apicloud 前后端分离，后端主要分层为控制器层，逻辑层，数据 层，代码高度封装。主要的系统有会员系统，推荐系统，推荐返现系统，订单系统，后台权限管理系统，项目 用到redis的geo存储记录地理位置信息，订单系统采取异步消息队列。服务器单机压测200rps
- 责任描述： 部署服务器环境，编写前端js及后端接口文档。在技术总监的指导下分模块完成代码。

 **walhao商城** :

- 项目描述：该项目是主要用于网上购物，主要包含用户注册登录，会员等级系统，购物车系统，商品系统（包含商品栏 目，商品品牌），支付系统（微信支付，支付宝，银联支付），包含退款系统，以及商家后台的RBC权限管 理系统。主要在商品搜索中用到sphinx.传统的C\S架构网站。包括多条件限制搜索，模板采用smarty模板 
- 责任描述：  本人是这个项目的负责任人。除了静态页面交由前端，所有功能的实现都由本人完成。 