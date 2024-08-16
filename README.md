**扫码 >> 源码商城 获取** ![qrcode_for_gh_1266b4b5294a_258 (2)](https://github.com/user-attachments/assets/45838afd-19a8-4cdc-bdd5-74b9c76fb241)

**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，不提供调试服务。项目仅供学习和毕业设计参考~**

#### 1.项目介绍

技术栈+工具：SpringBoot + JSP +MySQL + Maven +IDEA2022

系统角色：管理员、党务、普通用户

系统功能：管理员（栏目管理、信息咨询管理、公告管理、发布管理、轮播图管理、留言管理、用户管理、角色管理等）、党务（入党申请管理、党费出账、费用类别管理等等）、普通用户/门户（注册登录、入党申请、党建报告、党建交流、我的留言等）

#### 2.项目部署

- 创建数据库，导入项目中的sql

- 打开IDEA，导入项目party

- 根据本地数据库环境，修改数据库的连接信息 src/main/resources/application.properties 16-19行

- 启动项目，运行 http://localhost:8080/dangjian 普通用户账号/密码：13033333333/123456 

- http://localhost:8080/dangjian/admin/login.jsp 管理员账号/密码：admin/admin  党务账号/密码：dangwu1/123456 (普通用户不要在管理web页面登陆)
