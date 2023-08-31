### 作者QQ：1556708905(支持修改、 部署调试、 支持代做毕设)

#### 支持代做任何毕设论、接网站建设、小程序、H5、APP、各种系统等

**毕业设计所有选题地址 [https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

**博客地址：[https://blog.csdn.net/2303_76227485/article/details/128651462](https://blog.csdn.net/2303_76227485/article/details/128651462)**

**视频演示：[https://www.bilibili.com/video/BV18c411M7Jr/](https://www.bilibili.com/video/BV18c411M7Jr/)**

 
## 基于Springboot的教务管理系统、学生管理系统、课表查询系统 (源代码+数据库+实验报告)

## 一、系统介绍

本项目分为学生、老师、管理员三种角色

- 基于SpringBoot的教务管理系统、学生管理系统、课表查询系统 

- 后端使用Maven 进行包管理，使用spring-boot框架、模板引擎使用thymeleaf、web模块使用springMVC、数据库连接池使用Druid、数据库访问使用mybatis-plus、工具包使用hutool。前端使用H-ui模板，结合Timetables展示课程表。

- 系统能够实现用户的登录退出，教室、班级、院系、地点、教工、学生、用户、课程、课程表的分页展示、增加、删除（批量）、修改、根据条件查询，排课（课程表增删改查）、课程表通过表格展示（可以通过教师、班级、学年、学期进行筛选）。并且使用拦截器通过session判断用户是否登录。 

- 学生、老师可以查看自己的课表，修改自己的个人信息 、密码。登录、退出。

  ![1652330542964](picture/1652330542964.png)

## 二、所用技术

后端技术栈：

- springboot
- mybatis-plus
- mysql

前端技术栈：

- thymeleaf
- H-ui

- Timetables.js


## 三、环境介绍

基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7及以上,Maven

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图



![1652330565045](picture/1652330565045.png)![1652330581731](picture/1652330581731.png)

![1652330589467](picture/1652330589467.png)![1652330603075](picture/1652330603075.png)

![1652330607763](picture/1652330607763.png)

![1652330612295](picture/1652330612295.png)

![1652330616130](picture/1652330616130.png)

![1652330621640](picture/1652330621640.png)![1652330627860](picture/1652330627860.png)

![1652330638907](picture/1652330638907.png)

![1652330643420](picture/1652330643420.png)

![1652330647714](picture/1652330647714.png)

![1652330651946](picture/1652330651946.png)

![1652330655752](picture/1652330655752.png)

![1652330660007](picture/1652330660007.png)

![1652330664455](picture/1652330664455.png)

![1652330669111](picture/1652330669111.png)

![1652330677831](picture/1652330677831.png)

## 五、浏览地址

http://localhost:8112/

管理员账号：shf   密码：shf

老师账号：zhangsan   密码：zhangsan

学生账号：xue1 密码：xue1

## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行sms文件下sms.sql文件；
2. 使用IDEA/Eclipse导入项目，若为maven项目请选择maven;导入成功后请执行maven clean;maven install命令，然后运行；
3. 修改application.yml 里面的数据库配置
4. 启动项目后端项目 

 