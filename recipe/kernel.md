
# 个人信息

 - 王建兴/男/1991
 - 本科/河南理工大学自动化
 - 工作年限：5年
 - 技术博客：https://faxiang1230.github.io

 - 期望职位：Linux内核开发
 - 期望城市：北京
 
# 联系方式
- 手机：15313132056
- Email：wangjianxing5210@163.com
- 微信号：wangjx1129



# 工作经历
## 上海思芮有限公司 (2017年8月 ~ 至今)
### Android手持机
在项目中我主导项目的进度，评估技术方案，负责把控手持机项目整体实现。同时我也参与项目开发，攻克技术难题，调研新的技术方案实现，下面是我的一些具体工作：
1.Android系统项目中进行feature定制和bug修复
从framework,HAL,kernel,到uboot中功能实现，完成了2个系统级的功能定制，修复多个系统问题
2.负责基于ecryptfs的安全加密文件系统的工作
内核中加密文件系统的一种方案，为特定场景下定制加密方式
3.负责基于kernel LSM的安全检查功能
对于应用安装、执行、二进制文件和库的打开，在内核中做安全检查，类SELinux方案的定制化
4.调研并实现了一种用户层vpn方案
主要是为了解决局域网内网络通信加密的问题，将ipsec加密协议实现在用户空间中，避免内核不同版本的工作
## 清华大学计算机系(2016.05 -2017.08 )
### OPENTHOS系统
OPENTHOS是基于Android-x86的国产操作系统，将android移植到PC上运行，免费、开源，界面友好，能运行大量的android app

在项目中作为主要的系统工程师来一起构建定制OPENTHOS系统，负责具体系统性的工作，为android app开发人员提供底层支撑；

1.在硬件适配过程中，解决了很多系统稳定性问题，系统更加可靠。为OPENTHOS找到一些合适的方法和工具，并总结下来，方便其他同事解决这类问题
2.在显示方面做了重要改进:动态调整分辨率，双屏克隆功能，显示屏动态监测
3.完成系统的安装和升级工作，在更多的机器上可用，也能更加便捷地体验最新版OPENTHOS
4.做了一些代码管理方面的改进，引入代码审核服务、代码检索服务；同时也维护Android源码镜像，升级系统版本工作
5.为OPENTHOS提供了很多后端的服务支撑:账号管理、云同步服务
6.为OPENTHOS中做了很多的工具集调研，移植工具到OPENTHOS上
## 中科创达有限公司 （ 2014年3月 ~ 2016年5月 ）
在中科创达期间主要是在高通平台上进行手机项目开发工作，参与过项目的不同工作
### telephony开发(2014年3月~ 2015年4月 )
工作主要包含：
android framework层GSM Serivce、RIL、Qcril中通话，数据连接，短信，驻网方面的工作
Modem中NAS层协议工作
收获：养成了良好的工作习惯，学会了他人分享，共同协作，工作的责任心
### 功耗
实现手机在各种场景下电流的消耗:
低功耗状态vdd-min的控制:灭屏、静置时进入vdd-min状态，手机功耗极低;
常见使用场景下的电流控制:浏览网页,正常待机,wifi上网，拍照等状态时电流的消耗;
后期在公司中做过功耗方面的知识培训
收获:系统性问题的分析在于观察、分解，从整体上能够定位问题，逐步排查
### 稳定性
负责分析手机的各种crash问题:
1.使用QPST，ramdump、tomstone等方式获取日志信息
2.使用ramparser、crash等工具解析日志
3.分析系统crash的原因
系统重启的原因有很多:驱动,watchdog,锁等因素，还有常见的system_server的软watchdog引起系统重启.
