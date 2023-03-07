## 一、云上办公系统

### 1、介绍

云上办公系统是一套自动办公系统，用户可以通过手机微信扫码关注公众号，在公众号上进行OA审批流程

系统主要包含：管理端和员工端


管理端包含：权限管理、审批管理、公众号菜单管理

员工端采用微信公众号操作，包含：办公审批、微信授权登录、消息推送等功能



项目服务器端架构：SpringBoot + MyBatisPlus + SpringSecurity + Redis + Activiti+ MySQL

前端架构：vue-admin-template + Node.js + Npm + Vue + ElementUI + Axios



### 2、核心技术

| 基础框架：SpringBoot                                         |
| ------------------------------------------------------------ |
| 数据缓存：Redis                                              |
| 数据库：MySQL                                                |
| 权限控制：SpringSecurity                                     |
| 工作流引擎：Activiti                                         |
| 前端技术：vue-admin-template + Node.js + Npm + Vue + ElementUI + Axios |
| 微信公众号：公众号菜单 + 微信授权登录 + 消息推送             |


### 3、开发环境说明

| 工具         | 版本                                   |
| ------------ |--------------------------------------|
| 后台         | SpringBoot 2.3.6 + MyBatisPlus 3.4.1 |
| 服务器       | Tomcat 8.5.73                        |
| 数据库       | MySQL 8.0.27                         |
| Build Tools  | Maven 3.8.5                          |
| 前端         | Vue + ElementUI + Node.js            |
| 开发工具     | IDEA 2022.3                          |
| 版本管理工具 | Git                                  |


### 4、 个人总结
我认为该项目对我来说主要的帮助有：

1、项目是前后端分离的，符合目前主流业务开发逻辑，作为后端程序员，复习前端Vue + ElementUI框架， 巩固练习使用前端的脚手架工程，学习使用前后端联调开发过程

2、项目中引入JWT加密token，用作用户登录身份校验，用 SpringSecurity 来做权限控制，涉及多表查询，是项目的重难点学习对象，也是对前面学习SpringSecurity的一个巩固




3、前端使用微信公众号来作为接入口，以前没有开发过，也是亮点。



4、引入 工作流引擎：Activiti 作为组件，第一次用，学习下

5、集成Swagger，方便进行接口API的统一测试

### 5、开发的细节
个人博客地址：



