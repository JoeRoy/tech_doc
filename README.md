# 兰建华个人简历
# 联系方式

- 手机：15980660027 
- Email：wbsljh@163.com
- QQ：33650047
- 微信号：lanjianhua2010
- 户籍： 福建福州

---

# 个人信息

 - 兰建华/男/1986 
 - 本科/厦门集美大学 
 - 工作年限：9年
 - Github：https://github.com/wbsljh/

 - 期望职位：系统架构师，应用架构师
 - 期望薪资：税前月薪20k~30k，特别喜欢的公司可例外
 - 期望城市：福州

---

# 工作经历

## 北京亚信数据福州研发中心 平台研发工程师 （ 2016年8月 ~ 至今 ）

> 工作地点： 福州

### 组织研发大数据可视化平台

担任平台研发工程师，负责组织公司大数据可视化平台研发工作。 主要负责如下工作：

1、 对公司现有项目遇到的大数据可视化及报表相关需求进行调研分析，引入Airbnb开源的大数据探索式分析平台Superset

2、 实现Superset单点登入功能， 集成公司现有业务系统

3、 集成Echart，设计一套表单模型用于快速开发Echart图表组件， 并基本实现了所有基于Echart图表组件 

4、 实现一套机制封装自定义html组件，及html模板。

5、 实现在仪表盘中支持图表联动， 数据下钻

6、 实现基于Docker的自动化部署， 持续集成

- 技术架构

> 后台采用python flask sqlalchemy numpy pandas框架。前端用es6 reactjs

经过2个月时间完成了平台第一个版本开发， 并在公司内部多个项目投入生产使用， 基本上涉及到图表展示或者报表展示需求都能满足。 

### 参与信用评价系统开发

在信用评价系统中作为研发工程师， 负责信用指标及基本信息填报采编模块、 指标计算模块开发。


## 圈子里网络科技有限公司（ 2015年12月 ~ 2016年8月 ）

> 工作地点： 福州

### 圈子里APP

**圈子里APP**是服务于婚庆行业企业及行业内从业人员的垂直社交平台，我担任平台架构师，负责协助CTO组建技术团队，平台技术架构， 开发规范及技术管理规范定制， 后台基础核心服务开发， 及业务API开发。

工欲善其事必先利其器，在这个项目开发中， **首先**我负责制定和推广了Git版本管理规范和Code Review流程， 代码提交测试流程；制定服务端API规范，及与客户端交互接口规范， 统一采用Swagger作为在线API文档工具，极大的提高了代码交付测试的效率， 及服务端客户端沟通的效率， 更加明确了各方的指责和边界。

**其次**我搭建了服务端开发总体技术架构，服务端主要采用Java体系技术：

> Spring Boot SpringMVC Spring Data, Hibernate, Mysql, Mongodb, Elacsearch, Redis, Quartz Cluster Oauth2

根据系统业务特点为了加快开发速度， 在业务开发中， 充分理解业务需求重心放在核心的领域模型，建好实体模型后，用代码生成工具生成代码骨架包括（Dao, Service, Controller），其中代码生成工具经过调研后选择Jhipster。 大大提高了开发的速度，和提高了代码的整体质量， 更重要的是为后续服务拆分提供原生的支持（为了提高开发速度，并受资源限制，前期还是按单体应用模式开发）。

**第三**规划分布式任务调度系统，系统开发后期有大量定时提醒任务， 基于Quartz Cluster开发了独立的任务调度服务。

**第四** 聊天历史记录实时写入Mogodb

产品于2016年6月份正式上线，可在各大市场下载。


## 厦门多快好省网络科技有限公司 （ 2014年3月 ~ 2015年12月 ）

> 工作地点： 厦门

### 谁牛金融APP

担任多快好省旗下随牛社区金融平台数据及服务端研发小组组长， 主要负责：

1、 负责数据端、服务端应用架构设计， 并与CTO、技术经理一起参与技术架构设计

2、 负责草拟制定开发测试流程， 产品发布流程， 代码Code Review流程

3、 开发任务分解和分配

4、 培训新员工

5、 给团队其他成员培训金融投资相关业务，组织技术分享

6、 作为基础架构研发小组一员， 参与平台核心组件和功能模块开发

技术相关：

1、 参与爬虫系统开发， 用Scrapy框架

2、 参与股票实时行情计算系统开发， Kafka + Python程序 + Redis

3、 离线批量计算系统， Luigi

4、 股票提醒引擎开发， 大体思路是预先将需要提醒的对象处理好存放于redis中， 一旦股票提醒事件触发（比如上涨3%），直接给提醒对象发送提醒

5、 其他主要业务API开发


技术栈 

Mysql

Mongodb 存储股票公告，资讯等信息（数据量大 实时读 离线写）

Redis 存储高频访问的股票行情分时图，K线图，及其他缓存数据（session等） 

Kafka

Elacsearch

Python Django\Django-REST-Framework\

Celery 异步任务调度

Luigi 数据计算框架， 处理任务依赖关系，监控等
 
## 福州顶点软件 （ 2010年2月 ~ 2014年4月 ）

> 工作地点： 深圳、杭州

### 证券公司CRM系统

担任现场项目经理， 在全国多家券商组织实施落地CRM系统、数据仓库、BI系统。

其中比较有代表性的是中信证券， 该项目的目标是用顶点CRM系统替换已经运行6年多的金正股份CRM系统， 并向2大子公司推广。该项目面临2大挑战： 

1、替换已经运行6年的第三方的系统 

2、集团大型系统， 组织架构复杂， 要灵活考虑子公司个性化需求，在任期间完成了第一阶段母公司系统上线， 并正常运行3个月。

- 我负责的主要工作：

1、参与售前需求讨论，提供技术方案

2、需求规格说明书， 详细设计文档编写

3、组织开发， 培训新员工

4、组织现场项目例会，向公司及甲方工作组汇报阶段成果

5、组织项目培训、上线、验收工作

- 我的技术相关工作：

用Python开发现场运维相关监控和业务模块， 并被公司其他项目所采用， 比如批量短信发送引擎， 通过扫描业务系统写入的短信内容中间表，多线程并发提交短信内容至短信平台。

优化数据库索引，提升指标计算、薪酬计算、离线批处理计算程序运行瓶颈

其他包括外部接口Restfull、WebService调用插件开发、工作流配置、存储过程开发等

## 国网信通亿力吉奥有限公司 （ 2007年7月 ~ 2010年2月 ）

> 工作地点： 厦门

参与电网生产管理系统（简称GPMS）开发，在GPMS平台上担任以下几个模块的负责人：车辆调度管理系统、现场车辆位置信息实时查询系统、输电设施可靠性分析与运维成本管理系统。 

主要工作： 

1、与客户沟通需求，独立进行模块开发，用到的技术有ORCLE、JAVA(spring mvc  spring  mybatis hibernate)、Flex, Jquery, BootStrap 

2、到客户现场实施, 组织验收相关工作包括文档、培训、安排验收会议


## 开源项目

 - [jeesite-parent](https://github.com/wbsljh/jeesite-parent)：基于Jeesite框架，将模块按照工程进行拆分， 便于分布式部署

# 技能清单

以下均为我熟练使用的技能

- Web开发：Java/Python/
- Web框架：Spring MVC/Spring Boot/Django/Flask/
- ORM框架：Hibernate/Mybatis/SqlAlchemy/
- 工具：Git/Maven/Docker
- 前端框架：Bootstrap/ES6/HTML5/ReactJs/VueJS
- 前端工具：WebPack
- 中间件：Zookeeper, Kafka, ActiveMq
- 数据库相关：MySQL/PgSQL/Oracle/Mongodb/Hbase
- 版本管理、文档和自动化部署工具：Svn/Git/
- 单元测试：Junit
- 云和开放平台：SAE/BAE/AWS/微博开放平台/微信应用开发


---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
