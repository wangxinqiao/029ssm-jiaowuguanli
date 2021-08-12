# 029ssm教务信息查询系统
029ssm教务信息查询系统

### 简介
```
该项目是一个简单的教务查询系统，分别授予管理员，教师，学生不同的权限，达到基本的数据查询与修改操作。
管理员主要功能:
  课程管理、学生管理、教师管理；
教师主要功能：
  查看我教授的课程列表、查看学生成绩列表、给学生打分；
学生主要功能：
  查看所有课程列表、选课、查看所修课程等；
```

演示地址：[ **点此查看** ](http://www.csbishe.cn:15000/Examination_System/login.jsp;jsessionid=66941FEF358E181CC130026416994339)
````
管理员账号/密码：admin/admin
学生账号/密码： 10001/123456
教师账号/密码： 1001/123456
````
源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=130)

### 环境需要
```
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目 
6.数据库：MySql 5.7版本；
```

### 使用技术 
```
IOC容器：Spring
Web框架：SpringMVC ORM框架：Mybatis 安全框架：Shiro
数据源：C3P0 日志：log4j
前端框架：Bootstrap
```

### 使用说明
```
1. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，下载所需jar包；
2. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
3. 将项目中mysql.properties配置文件中的数据库配置改为自己的配置
4. 配置tomcat，然后运行项目，输入localhost:8080/xxx 登录
5. 管理员账户:admin  密码:123
教师账号：1001 密码:123
学生账号：10001 密码:123
```

### 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/093132_c9681dbb_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/093146_750f322c_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/093257_17271bef_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/093306_694a0cc5_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/093316_44d252fd_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/093326_a9aa70fc_863230.png "屏幕截图.png")



