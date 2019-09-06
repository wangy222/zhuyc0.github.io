# 联系方式
- 手机：18166334886
- Email：zyc199777@outlook.com
- QQ：1138613536

# 个人信息

 - 朱屹晨/男/1997 
 - 本科/重庆工程学院-软件工程(2015~2019)
 - 工作经验：1年
 - 期望职位：Java工程师
 - 期望薪资：6k+

---

# 工作经历

## 北京雷云智链科技有限公司(2019.4~2019.8)

### 阳光福利商城

该项目是给企业员工发放福利的购物商城,我负责商品数据获取,提供商品索引接口,APP消息推送和后台管理界面。

商城中的部分商品来自于京东,通过他们的接口请求商品入库,使用Spring boot提供的RestTemplate进行请求,为加速使用多线程获取,遇到响应速度大于入库速度的问题,用到MQ。每个星期都要获取就用Quartz做定时任务。从队列中取出到入库使用Spring Batch处理。

创建索引使用ES,把表数据放到ES中,部分自营商品在其他库,使用多数据源。对中文分词使用IK。使用spring Data Elasticsear + ElasticsearchTemplate 对索引进行操作。

APP端消息推送使用MQ+激光。

使用vue+element开发了管理界面,对取到的商品要进行归类。获取商品的和创建索引的实时进度存放在Atomic类中用WebSocket推送到前端。

在CentOS部署环境,JDK,mysql,Redis,Docker,rabbitMQ,ES,Kibana,nginx,目前三个springBoot项目和一个vue项目用Git+Gitee管理,用Alibaba Cloud Toolkit一键部署。

## 重庆跃医通科技有限公司 （ 2018.9 ~ 2019.4 ）

### 孕产妇保健系统 
我负责孕妇体检信息维护这块，获取Form数据，JS通过Ajax请求后台API。Controller处理请求，页面跳转和DTO的验证和处理，构造DO，调用Service进行数据库存储。或者查询DO构造VO返回到前端，通过JQuery赋值到Form表单上，有的页面是ModelAndView通过JSP标签渲染。


### 妇幼信息化管理平台
我参与儿童保健这块的界面原型的绘制，数据字典筛选，数据库字段梳理，PowerDesigner 数据模型创建，表结构创建。目前投标演示版已经完成，正在开发web 1.0版。

​	界面原型绘制：编写Html，JS的公共方法，由于要求兼容IE8，这里遇到了点困难，很多JS库不支持IE8。

​	数据库字段和数据字典：先整理该模块的，然后项目组讨论，在PowerDesigner上呈现，通过脚本生产表。

​    web开发：ss+mybatis plus+shiro+ehcache+ligerUI，儿保的页面跳转，表单验证，Form赋值。

---

# 学校项目
## 水果拼团系统

毕业设计项目，Maven 模块化开发，后台Spring Boot提供Restful API, Security安全框架细粒度级验证，统一返回类型，全局异常处理。管理界面用Layui编写，商城界面用Vue+Element编写，通过Nginx代理实现前后端分离。JWT保障API安全访问。

 - [FGS](https://github.com/zhuyc0/FGS)：[FGS-html](https://github.com/zhuyc0/FGS-Html) : [FGS-vue](https://github.com/zhuyc0/FGS-vue) 

   项目收获：vue前端框架，mvvm模型，基本指令，vue-cli, vuex, axios, pusub-js, JWT

### 教师评价系统

期末实训项目，spring boot + mybatis + shiro + layui，基于注解的Redis缓存, POI 解析Excel文件, thymeleaf模板引擎，shiro粗粒度过滤。

- [tesystem](https://github.com/zhuyc0/tesystem)

  项目收获：yaml文件，缓存，nosql ，MultipartFile，POI解析Excel，websocket

### 在线学习系统

期末实训项目，spring boot + mybatis + security + layui，Maven 模块化开发，动态菜单分配，注解权限管理。文件上传与下载，视频文件的处理 video.js，Oracle数据库

- [OSS](https://github.com/zhuyc0/OSS)

  项目收获：权限管理，oracle数据库的使用，JQuery插件

# 技能清单
- 后端开发：Spring boot / Spring Cloud
- 前端开发：H5/ Vue / JQuery / Layui / Sass
- 数据库相关：MySQL/ ORACLE/ Redis/ Mybatis/ Mybatis Plus
- 版本管理、文档和项目构建工具：Svn / Git / Maven / Gitee / Github
- 测试工具： PostMan / Idea / Chrome JS 调试
- 云和服务器：阿里云 / Nginx 

---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
