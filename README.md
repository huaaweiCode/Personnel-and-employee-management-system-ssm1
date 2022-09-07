# 人事员工管理系统SSM

## 1、项目介绍

基于SSM的人事员工管理系统共有两种角色，分别为管理员和员工，功能如下：

* 管理员：部门管理、员工管理、职位管理、公告管理、文档管理

* 员工：查看部门、员工、职位、公告等信息


## 2、项目技术

后端框架：SSM（Spring、SpringMVC、Mybatis）

前端框架：Layui、jsp、css、JavaScript、JQuery

## 3、开发环境

- JAVA版本：JDK1.8，其它版本理论上可以
- IDE类型：IDEA、Eclipse、Myeclipse都可以。推荐IDEA与Eclipse
- tomcat版本：Tomcat 7.x、8.x、9.x、10.x版本均可
- 数据库版本：MySql 5.x
- maven项目：否
- 硬件环境：Windows 或者 Mac OS


## 4、功能介绍

### 4.1登录界面

![登录](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220508205543.png)

管理员和职工均可以通过此页面登录至不同的功能主页。

### 4.2管理员功能模块

![管理员-用户列表](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220508205555.png)

![管理员-员工列表](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220508205558.png)

![管理员-添加员工](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220508205603.png)

![管理员-职位列表](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220508205609.png)

- 用户管理的功能包括：添加用户;查询用户，可以查询所有用户或根据用户名和用户状态进行模糊查询，删除、修改用户
- 部门管理的功能包括：添加部门，查询部门，可以查询所有部门或根据部门名称进行模糊查询，删除部门，修改部门
- 职位管理的功能包括：添加职位，查询职位，可以查询所有职位或根据职位名称进行模糊查询，删除职位，修改职位
- 员工管理的功能包括：添加员工，查询员工，可以查询所有员工或根据员工姓名，身份证号，手机号，性别，职位，部门进行模糊查询，删除员工，修改员工
- 公告管理的功能包括：添加公告，查询公告，可以查询所有公告或根据公告名称，公告内容进行模糊查询，删除公告，修改公告
- 下载中心的功能包括：上传文件，查看文件，可以查询所有文件或根据文件标题进行模糊查询。

### 4.4 职工功能模块

![职工界面](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220508205654.png)

职工权限受限，只可查看部门、用户、职位、公告等信息，不能修改或者添加。





