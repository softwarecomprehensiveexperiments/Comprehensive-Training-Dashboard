#### 软件需求规格说明书

## 1.  引言

本文的目的是：

a.定义软件总体需求，作为用户和软件开发人员之间相互了解的基础；

b.提供性能要求、初步设计和对用户影响的信息，作为软件人员进行软件结构设计和编码的基础；

c.作为软件总体测试的依据。

## 2.软件总体概述

  “闲钱袋鼠”小程序是大学生通过做任务挣钱的云平台，它属于以运营为中心的服务软件，也可以理解为面向大学生的专业“众包”系统。系统非常简单：有一个云服务中心，其业务在不断完善中；每个学生都有“闲钱袋鼠”客户端；学生也可以提供任务给平台。基本业务是，发布者发布任务要求与薪酬，系统推送到客户端，学生完成任务可获得系统内部的“闲钱币”，“闲钱币”可用于发布任务或提现。系统不支持零元交易。挣闲钱系统包括是个人信息管理系统、任务管理系统、交易管理系统、账户管理系统等
  

## 3.用例建模与活动图

  ![](/images/用例图活动图.png)

用户可以查询余额，有充值功能
  ![](/images/账户管理活动图.png)
      
可以查看历史任务，能够显示完成的任务和取消的任务 
  ![](/images/任务管理活动图.png)

## 4.领域建模

  ![](/images/领域模型.png)

## 5.状态建模

  ![](/images/状态模型.png)

## 6.功能模型

  用户填写用户名、手机号和密码（界面上会有格式要求），符合格式要求即可注册
  ![](/images/用户注册.png)

  用户名和密码经验证对应即可登录
  ![](/images/用户登录.png)  

  用户可以在广场上查看当前可以选择的任务，可以通过点击任务来查看详情，并接受
  ![](/images/接受任务.png)    

  用户选择任务类型后，系统根据不同类型的任务弹出不同界面，用户填写完任务标题、内容、截止日期和悬赏后即可发布任务
  ![](/images/发布任务.png)

  用户可以查看或修改自己的个人信息
  ![](/images/修改个人信息.png)


## 7.用户特点
本软件的用户为大学生，学习能力普遍较好

## 8.开发环境约束

操作系统：win7及以上版本windows

开发工具：微信web开发者工具、idea

编程语言：java,javascript

