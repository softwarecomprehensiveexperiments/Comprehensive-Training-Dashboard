## 用户手册
#### 1. 引言
###### 1.1编写目的
编写用户操作手册的目的在于更好的服务于广大使用者，使用户能够快捷的掌握此软件的各项功能。 并且为用户更好的了解此软件提供了便捷的条件
预期读者：系统分析与设计教学团队、软件工程综合实验教学团队、使用该软件的开发人员、大学城学生用户、微信小程序审核团队
###### 1.2项目背景
a.待开发软件的名称： 闲钱袋鼠微信小程序
b.本项目提出者： SYSU课程组
c. 开发者： SYSU软件工程专业闲钱袋鼠课程小组
d. 预期用户： SYSU教学团队，成绩评定人员，此软件的开发人员，大学城大学生（中山大学、华南理工大学、广东外语外贸大学、星海音乐学院、华南师范大学）本科生、研究生、博士生
该软件同其他软件关系： 本软件参考《美团》、《天天跑腿》、设计
###### 1.3 定义
闲钱袋鼠：中山大学数据科学与计算机学院大三软件班的 6 位同学组成的开发团队。
其开发项目：基于微信小程序前端(wxml\wxss\js），JAVA后端框架，腾讯云服务器 。
闲钱袋鼠：袋鼠形象的灵活的行动方式，我们团队使用快速开发的开发模式，更在意更新与维护，且袋鼠的大大的袋子展示着我们小组对于产品效果的向往，对于软件实现功能的情况下，用户使用简单明确的追求
小程序名：idlemoneykangaroo
###### 1.4参考资料
程序开发实用案例王晓 9787302160557 清华大学出版社
从入门到精通 XML完全开发指南 孙更等 9787030211743 科学出版社
Web Services 原理与研 顾宁 等9787111174615 机械工业出版社
发实践 编着SOAP:XML 跨平台 Web 塞利 著；杨9787111095170 机械工业出版社
Service 开发技术 涛 等译XML Web Service 开发 微软公司 7040158256 高等教育出版社

#### 2. 软件概述
###### 2.1 目标
大学生的学习生活中有很多的烦恼，我们的闲钱袋鼠就会让大学生用少量的金钱得到最方便的服务：不用再发红包求别人填问卷、不用再自己默默取十公斤的快递，这些任务可以以问卷的形势征集信息，可以拜托别人跑腿，为使⽤者提供了极⼤的便利，通过线上发布，线上回收，线上统计的⽅式，使⽤者可以清楚的了解发布问卷的功能。
###### 2.2功能
发布问卷任务、跑腿任务、资源分享任务，具有充值、接单、放弃任务、生成问卷、填写问卷、双边共确认保证任务完成度、储存用户信息、变更以及充值袋鼠币的功能
###### 2.3性能
a.数据精确度 ：最高输入string0-140 int0-13 输出精度98%数据处理时采用取整运算基本没有数据损失
b.时间特性：页面响应时间最长631ms，最短120ms，页面渲染时间最长1251ms（手机情况）最短150ms，网络请求时延80ms
c.灵活性 在操作方式、运行环境需做某些变更时软件的适应能力。由于本项目在微信提供的小程序框架中完成，有很多的，使用了很多的微信组件，所以移植性较差，但根据微信的普及性，用户想要更换设备后使用闲钱袋鼠小程序也更加方便，只需要下载一个微最新版即可，所以灵活性很强。

#### 3. 运行环境
###### 3.1硬件
a. 计算机型号、主存容量：windows7及以上、ios9.0及以上（可以在Appstore安装微信运行内存3G及以上物理内存20G以及以上，现测试设备为戴尔游匣7300、联想拯救者5300、腾讯云服务器
 b. 手机设备型号及数量：现在用户实测已经完成10个用户同时使用，预计服务器设计为100人，现测试设备为ANE-AL00、Oneplus7pro
###### 3.2支持软件
微信v7.0版本及以上

#### 4. 使用说明
###### 4.1



![在这里插入图片描述](https://img-blog.csdnimg.cn/20190627222259623.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MzQ5Mjg1,size_16,color_FFFFFF,t_70)





![在这里插入图片描述](https://img-blog.csdnimg.cn/20190627222323149.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MzQ5Mjg1,size_16,color_FFFFFF,t_70)















![在这里插入图片描述](https://img-blog.csdnimg.cn/20190627222356254.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MzQ5Mjg1,size_16,color_FFFFFF,t_70)
















![在这里插入图片描述](https://img-blog.csdnimg.cn/20190627222404732.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MzQ5Mjg1,size_16,color_FFFFFF,t_70)














![在这里插入图片描述](https://img-blog.csdnimg.cn/20190627222411301.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MzQ5Mjg1,size_16,color_FFFFFF,t_70)





![在这里插入图片描述](https://img-blog.csdnimg.cn/20190627222433521.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MzQ5Mjg1,size_16,color_FFFFFF,t_70)










![在这里插入图片描述](https://img-blog.csdnimg.cn/20190627222508588.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MzQ5Mjg1,size_16,color_FFFFFF,t_70)













![在这里插入图片描述](https://img-blog.csdnimg.cn/20190627222520857.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM2MzQ5Mjg1,size_16,color_FFFFFF,t_70)













![在这里插入图片描述](https://img-blog.csdnimg.cn/20190627222530230.png)








###### 4.2求助查询
前端显示问题：陈金坤
电话15920804647
微信KkBeifeng
后端数据问题：陈吉凡
电话15027239913
微信cjf-iiiiiiii100



#### 5. 非常规过程
页面不加载
上拉数据不刷新
袋鼠币数值不正常
信誉值不正常
任务问卷数据问题
无法正常接收发布任务
点击按钮没有反应
用户信息没有更新

#### 6. 操作方式
移动端使用触摸按钮的模式激活小程序的响应逻辑函数或者发送网络请求

