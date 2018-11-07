JavaEEDeveloperBook
注: 参考传智播客的JAVA EE的路线，内容会根据事情情况改动，也会添加自己 的内容在里面，是一个不断修改和完善的过程。

参考资料：

小马哥Java SE基础视频
Java基础案例教程 黑马程序员 编著
传智播客Java EE学习路线
Part I - Java语言入门
内容01-基础语法

Hello World
常量
变量
数据类型
运算符
方法
流程控制语句
Eclipse IDEA使用
数组
内容02-面向对象

类
对象、继承、多态
构造器
super、this
接口、抽象类
权限修饰符
内部类
Random、ArrayList、String、Arrays、Math
掌握的能力

Java开发环境的基本配置
运算符、表达式、流程控制语句、数组等的作用
使用eclipse、idea开发工具
Java基本面向对象知识
常用类String、ArrayList等的使用
Part II - Java语言高级
常用API

Date
DateFormat
Calendar
System
StringBuilder
集合API

Collection
泛型
List
Set
Collections
Map
HashMap
异常

异常体系
异常分类
声明抛出捕获异常
自定义异常
多线程

线程概念
线程同步
Lock
线程生命周期
线程池
Lambda表达式

函数式思想概述
Lambda标准格式
Lambda语法与注意事项
IO流

文件
字节流
字符流
转换流、高效流
网络编程

网络编程三要素
Socket原理机制
UDP传输
TCP传输
新特性

函数式接口
方法引用
函数式编程
Stream流
掌握的能力

Java面向对象相关知识点
开发中常用类如集合、IO流、时间日期等操作
Java异常处理机制，Java多线程开发
网络基础知识，了解Socket原理，TCP、UDP协议
java基本语法完成单机程序的编写
java新特性，如Lambda、Stream流等操作
Part II - JavaWeb
mysql与jdbc

mysql
jdbc
连接池
JdbcTemplate
前端技术

html5
css3
javascript
bootstrap
linux与nginx

linux安装
目录操作
文件操作
网络操作等
nginx安装、配置、部署
基础加强

反射
BeanUtils
注解
xml与jsoup

xml基本语法
约束
jsoup概述
jsoup作用使用
xpath
servlet核心编程

tomcat
request、response
cookie、session
jsp、el、jstl、Filter
web异步开发

jquery3
ajax
json
redis

nosql介绍
redis数据类型
常用命令
jedis
maven

maven概念与作用
idea集成maven
maven常用命令
依赖管理
旅游网站

baseServlet优化
redis缓存
jdbcTemplate事物控制
linux shell编程
项目部署
掌握的能力
Java JDBC、连接池操作、熟练操作mysql数据库
web开发常用知识如：html5、css3、javascript、bootstrap、jquery等
javaweb开发核心技术Servlet、Listener、Filter等
linux服务器，并安装开发常用软件tomact、mysql、nginx等
同步及异步操作的javaweb开发，具备B/S结构软件开发能力，完成基本的javaweb项目
基本的项目管理工具maven的使用
Part III - 项目01
mybatis

自定义mybatis框架
mybatis入门
架构分析
常用API
配置与事务管理
mapper代理
数据封装
动态sql
关联查询
性能优化
查询缓存
spring

spring体系结构
spring配置
bean管理
IOC/DI、AOP
事务管理
spring5新特性
spring mvc

spring mvc 概述
控制器
常用注释
参数绑定
json数据交换
resutful
拦截器
文件上传
异常处理
SSM整合
oracle

安装配置
表空间
常用函数
多表查询
子查询
序列、视图
查询优化
PLSQL
存储过程
存储函数、触发器
maven

maven分模块构建
私服
本地仓库
框架-后台权限管理

svn
adminLTE
SSM零配置整合
spring security
权限控制
AOP日志
四个项目：物流行业-国际物流 电商行业-品优购 金融行业-易起贷 企业级服务-SaasOA

分布式框架Dubbox
采用angularjs作为前端框架，所有工程均采用ajax方式异步获取数据
使用select2多选下拉框组件
电商模式由原来的B2C升级为B2B2C
使用代码生成器生成代码
使用spring security作为安全框架
采用BCrypt加密算法
使用SpringDataRedis框架操作Redis
使用Spring Data Solr框架操作solr
Solr动态域（Dynamic）知识点
SPU和SKU
SpringBoot框架
阿里大于短信发送功能
使用CAS实现单点登录
使用CORS实现跨域
使用twitter的snowflake算法实现分布式ID生成器
微信扫码支付
电商秒杀解决方案
使用SpringTask实现任务调度
使用MavenProfilel实现开发与生产环境切换
掌握的能力

企业中最常用SSM框架开发，开发出结构清晰、可复用性好、维护方便的企业级应用程序
Angularjs框架
Spring security框架
dubbox分布式调用技术
zookeeper分布式应用协调服务
Freemarker模板引擎
全文检索解决方案
spring boot1.x框架的基本应用
CAS实现单点登录
CORS实现跨域
微信扫码支付
电商秒杀解决方案
SpringTask实现任务调度
MavenProfilel实现开发与生产环境切换
电商开发中的相关业务模块如商品、订单基本操作
电商开发中相关术语SPU和SKU等
积累互联网电商项目开发经营
Part III - 项目02
lucene/elasticsearch

什么是全文检索
Lucenne实现全文检索
Analyzer分析器
索引维护
ElasticSearch简介
ElasticSearch安装与启动
ElasticSearch核心概念、操作入门
ElasticSearch集成IK分词器
ElasticSearch常用编程操作
spring data ElasticSearch使用
spring data jpa

ORM框架介绍
hibernate框架介绍
JPA介绍
spring data jpa概述
spring data jpa常用操作
spring data jpa关联映射与多表操作
spring boot

springBoot简介（Spring Boot 2.0 新特性）
springBoot快速入门(包括热部署)
springBoot与其他技术的整合(SpringMVC\Spring Data JPA\JUnit\mybatis)
springBoot原理分析
thymeleaf模板语言
综合案例(Spring Data JPA + SpringBoot2.0 + thymeleaf)
Spring Boot Admin
git

git历史
git与svn对比
git工作流程
git安装
git管理文件版本
远程仓库
分支管理
vue.js

vue.js概述
vue.js系统指令
vue.js过滤器
vue.js ajax操作
vue.js组件介绍
vue.js路由
爬虫

爬虫介绍
httpClient
webMagic
四个项目：社交行业-十次方 教育行业-学成在线 生活服务-好客租房 医疗行业-传智健康

采用前后端分离的方式进行系统开发
采用模块化的课程设计，分为微服务开发、前端系统开发、爬虫与人工智能开发三个模块
SpringBoot2.0
Postman工具的使用
使用阿里云OSS实现图片资源的存储
使用MongoDB数据库
SpringDataMongoDB框架
使用Elasticsearch5.0实现搜索数据的存储
使用RabbitMQ作为消息中间件
使用JWT实现微服务鉴权
微服务框架Spring Cloud
分布式日志系统ELK
持续集成技术Jenkins
使用Rancher实现容器部署管理
使用Grafana实现服务的实时监控
Node.js的讲解
使用npm和cnpm管理包资源
使用webpack实现前端工程的打包
es6语法的讲解与应用
使用ESlint进行前端语法校验
axios的讲解与应用
使用vscode作为前端开发工具
使用mock.js与easyMock实现模拟后端API接口
使用Swagger语言作为文档设计规范
采用vue.js作为前端框架
使用ElementUI开发管理后台的前端工程
使用NUXT实现服务端渲染
分享组件的使用(QQ QQ空间 微信 新浪微博)
使用瀑布流组件实现前台页面数据的加载
使用爬虫框架webmagic爬取数据
使用spark mllib als 机器学习算法库实现智能分类
使用DL4J深度学习框架实现智能推荐
掌握的能力

基本的Java爬虫开发，webmagic爬虫框架使用
httpClient的使用
Spring boot2.x框架
Spring Cloud框架
MongoDB数据库使用
RabbitMQ消息中间件使用
Elasticsearch分布式搜索引擎
Rancher实现容器部署管理
Grafana实现服务的实时监控
node.js环境,使用npm和cnpm管理包资源
ESlint进行前端语法校验
axios的使用
vuejs框架的基本使用
瀑布流组件使用
前端页面分享功能的实现
企业级DevOps解决方案，熟悉Docker、Jenkins、Git等
spark mllib als 机器学习算法库实现智能分类
DL4J深度学习框架实现智能推荐