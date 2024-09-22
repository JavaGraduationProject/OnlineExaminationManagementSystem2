# 全目录

[更多系统、论文，供君选择 ~~>](https://www.yuque.com/wisebit/blog)

# 51.OnlineExaminationManagementSystem2

<p>群: 983063232(入群获取sql文件)</p>
<p>QQ: 206157502(加好友获取sql文件)</p>

<p><h1 align="center">51.在线考试管理系统</h1></p>


<p align="center">
	<img src="https://img.shields.io/badge/jdk-1.8-orange.svg"/>
    <img src="https://img.shields.io/badge/spring-5.x-lightgrey.svg"/>
    <img src="https://img.shields.io/badge/springmvc-3.x-blue.svg"/>
    <img src="https://img.shields.io/badge/mybatis-3.x-blue.svg"/>
</p>

# 简介


> 本代码来源于网络,仅供学习参考使用,请入群(983063232)后联系群主索要sql文件!
>
> 提供1.远程部署/2.修改代码/3.设计文档指导/4.框架代码讲解等服务
>
> 前端登录地址: http://localhost:8080/
> 
> 学生登录用户名: 311409030311  密码: 123
> 
> 老师登录用户名: 123  密码: 123
> 
> 管理员登录地址: http://localhost:8080/admin/login
> 
> 管理员登录用户名: 456  密码: 123



# 环境

- <b>IntelliJ IDEA 2009.3</b>

- <b>Mysql 5.7.26</b>

- <b>Tomcat 7.0.73</b>

- <b>JDK 1.8</b>

## 概述
这个项目是我的本科毕设作品，完全的个人项目，在工作几个月后，突然觉得应该好好写一写readme。该考试系统的用户类型有三种：教师、学生、管理员。
系统实现了一张试卷从产生到被做再到被评分的一系列过程。代码中注释十分详细，适合同样在做该课题的毕业生参考。
## 技术栈
* 前端：AdminLTE bootstrap jQuery ajax jsp
* 后端：java8 ssm框架 mvc模式 maven
* 数据库：mysql
## 系统主要实现功能
### 教师端
* 个人设置：更换密码。
* 课程管理：教师添加自己的任课课程信息，默认一个课程只能有一个老师。
* 试题管理：教师可以通过添加试题丰富题库，也可以对已存在的题目进行修改和删除操作。
* 试卷管理：教师首先创建或选择试卷模版，系统会根据模版自动从题库中抽取题目进行组卷。
* 考试管理：试卷产生后会自动出现在学生考试系统中，若需要取消考试，可以在此处设置。
* 试卷复查：考生的主观题答案会被保存到数据库中，教师可以对其进行复查。
* 成绩统计分析：本系统可以根据特定课程或特定班级使用柱状图，折线图，数据罗列等方式帮助教师更直观得了解学生成绩情况。
* 系统网盘：教师可以上传资料到网盘供学生下载学习
## 学生端
* 个人信息管理：登录密码修改。
* 我的考试：学生进入后会看到试卷信息，当有需要参加的考试时，点击进入即可来到考试界面。
  考试结束系统会自动提交考卷并完成自动改卷任务。
* 我的成绩：展示每门考试的成绩列表。
* 成绩分析：系统会统计出该生本学期参加每门考试的成绩，以及该门课程的平均成绩，使用雷达图进行对比。
* 系统网盘：学生只能下载网盘中的资料,不能上传
## 管理端
* 基本数据管理：对系统内置数据的录入。
* 系统维护：查看系统日志，接收用户问题反馈。
* 系统公告管理：在必要时发布系统公告，如系统版本更新等
## 启动说明
一、 操作环境
1. JDK:1.8
2. Mysql:5.6及以上
3. 编辑器:idea任意版本

二、 初始化数据库
1. 创建数据库
2. 执行SQL文件

三、 idea启动配置
1. 修改配置文件/resources/config.properties中数据库名、用户名称、密码。
2. 点击idea右上角锤子旁边的下拉选择，选择Edit Configuration。
3. 配置一个maven启动，command line设置命令： clean tomcat7:run。
4. 点击旁边的绿色三小按钮运行即可。

## 缩略图

![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/aa58ff23-07f8-47f1-9925-3de4d2a6133f.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/e5a81b29-fee0-40ff-a292-18a7eb88e244.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/ec66af42-bab9-41d2-b6fb-b310ccf70473.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/e7e2c097-0037-4e4f-bef4-4f0ecca27336.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/35490c6d-06f5-40a9-9622-73a0f3aa082c.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/ced78d31-9edc-451a-8caa-f02a31eca13f.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/45ba9112-1d13-41b2-bf86-96dfedd8365e.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/263ae036-561b-4693-ac0d-f51e35f99e43.png)


