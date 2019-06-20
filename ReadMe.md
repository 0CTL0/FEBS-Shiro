### FEBS-Shiro 2.0
![https://img.shields.io/badge/license-MIT-blue.svg?longCache=true&style=flat-square](https://img.shields.io/badge/license-MIT-blue.svg?longCache=true&style=flat-square)
![https://img.shields.io/badge/download-1k%2Fm-green.svg?longCache=true&style=flat-square](https://img.shields.io/badge/download-1k%2Fm-green.svg?longCache=true&style=flat-square)
![https://img.shields.io/badge/springboot-2.1.3-yellow.svg?style=flat-square](https://img.shields.io/badge/springboot-2.1.3-yellow.svg?style=flat-square)
![https://img.shields.io/badge/shiro-1.4.0-orange.svg?longCache=true&style=flat-square](https://img.shields.io/badge/shiro-1.4.0-orange.svg?longCache=true&style=flat-square)
![https://img.shields.io/badge/layui-2.5.4-brightgreen.svg?longCache=true&style=flat-square](https://img.shields.io/badge/layui-2.5.4-brightgreen.svg?longCache=true&style=flat-square)

FEBS-Shiro是一款简单高效的后台权限管理系统，使用Spring Boot，Shiro和Layui构建。FEBS意指：**F**ast，**E**asy use，**B**eautiful和**S**afe。相信无论作为企业级应用，私活开发脚手架或者权限系统构建学习，FEBS-Shiro都会是一个不错的选择。

### 演示地址

地址：[http://49.234.20.223:8080/login](http://49.234.20.223:8080/login)

演示环境账号密码：

账号 | 密码| 权限
---|---|---
scott | 1234qwer | 注册账户，拥有查看，新增权限（新增用户除外）和导出Excel权限


本地部署账号密码：

账号 | 密码| 权限
---|---|---
mrbird | 1234qwer |超级管理员，拥有所有增删改查权限
scott | 1234qwer | 注册账户，拥有查看，新增权限（新增用户除外）和导出Excel权限
micaela | 1234qwer |系统监测员，负责整个系统监控模块
Jana   | 1234qwer  |跑批人员，负责任务调度跑批模块

### 更多版本
当前分支为2.0版本，页面采用Layui全新构建，FEBS的其他版本：

名称 | 描述| 地址
---|---|---
FEBS-Shiro 1.x | Spring Boot 2.0.4 & Shiro1.4.0 权限管理系统（单页）。 | [https://github.com/wuyouzhuguli/FEBS-Shiro/tree/mysql](https://github.com/wuyouzhuguli/FEBS-Shiro/tree/mysql)
FEBS-Security | Spring Boot 2.0.4 & Spring Security 5.0.7 权限管理系统（单页）。 | [https://github.com/wuyouzhuguli/FEBS-Security](https://github.com/wuyouzhuguli/FEBS-Security)
FEBS-Vue | FEBS-Shiro前后端分离版本，前端架构采用Vue全家桶。 | [https://github.com/wuyouzhuguli/FEBS-Vue](https://github.com/wuyouzhuguli/FEBS-Vue)

### 系统模块
系统功能模块组成如下所示：
```
├─系统管理
│  ├─用户管理
│  ├─角色管理
│  ├─菜单管理
│  └─部门管理
├─系统监控
│  ├─在线用户
│  ├─系统日志
│  ├─登录日志
│  ├─Redis监控
│  ├─Redis终端
│  ├─请求追踪
│  ├─系统信息
│  │  ├─JVM信息
│  │  ├─TOMCAT信息
│  │  └─服务器信息
├─任务调度
│  ├─定时任务
│  └─调度日志
├─代码生成
│  ├─生成配置
│  ├─代码生成
└─其他模块
   ├─FEBS组件
   │  ├─表单组件
   │  ├─表单组合
   │  ├─FEBS工具
   │  ├─系统图标
   │  └─其他组件
   ├─APEX图表
   ├─高德地图
   └─导入导出
```
### 系统特点

1. 前后端请求参数校验

2. 支持Excel导入导出

3. 前端页面布局多样化，主题多样化

4. 支持多数据源，代码生成

5. 多Tab页面，适合企业应用

6. 用户权限动态刷新

7. 浏览器兼容性好，页面支持PC，Pad和移动端。

8. 代码简单，结构清晰

### 技术选型

#### 后端
- [Spring Boot 2.1.3](http://spring.io/projects/spring-boot/)
- [Mybatis-Plus](https://mp.baomidou.com/guide/)
- [MySQL 5.7.x](https://dev.mysql.com/downloads/mysql/5.7.html#downloads),[Hikari](https://brettwooldridge.github.io/HikariCP/),[Redis](https://redis.io/)
- [Shiro](http://shiro.apache.org/)

#### 前端
- [Layui 2.5.4](https://www.layui.com/)
- [Nepadmin](https://gitee.com/june000/nep-admin)
- [formSelects 4.x 多选框](https://hnzzmsf.github.io/example/example_v4.html)
- [eleTree 树组件](https://layuiextend.hsianglee.cn/eletree/)
- [formSelect.js树形下拉](https://wujiawei0926.gitee.io/treeselect/docs/doc.html)
- [Apexcharts图表](https://apexcharts.com/)

### 系统截图

#### PC端
![screenshot](screenshot/pc_screenshot_1.jpg)
![screenshot](screenshot/pc_screenshot_2.jpg)
![screenshot](screenshot/pc_screenshot_3.jpg)
![screenshot](screenshot/pc_screenshot_4.jpg)
![screenshot](screenshot/pc_screenshot_5.jpg)
![screenshot](screenshot/pc_screenshot_6.jpg)

#### 手机
![screenshot](screenshot/mobile_screenshot_1.jpg)
![screenshot](screenshot/mobile_screenshot_2.jpg)
#### Pad
![screenshot](screenshot/pad_screenshot_1.jpg)
![screenshot](screenshot/pad_screenshot_2.jpg)
![screenshot](screenshot/pad_screenshot_3.jpg)
### 浏览器兼容
|[<img src="https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png" alt="Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari |[<img src="https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Opera
| --------- | --------- | --------- | --------- | --------- |--------- |
|IE 10+| Edge| last 15 versions| last 15 versions| last 10 versions| last 15 versions
### 参与贡献
欢迎提交PR一起完善项目，以下为提PR并合并的小伙伴（排名不分先后）：

<a href="https://github.com/everhopingandwaiting">
    <img src="https://avatars3.githubusercontent.com/u/6021724?s=400&v=4" width="45px"></a>
<a href="https://github.com/mgzu">
    <img src="https://avatars1.githubusercontent.com/u/29629221?s=400&v=4" width="45px"></a>
<a href="https://github.com/yuuki80code">
    <img src="https://avatars0.githubusercontent.com/u/17798853?s=400&v=4" width="45px"></a>
<a href="https://github.com/cinsin">
        <img src="https://avatars1.githubusercontent.com/u/12856067?s=400&v=4" width="45px"></a>
<a href="https://github.com/Minnull">
    <img src="https://avatars2.githubusercontent.com/u/19608781?s=400&v=4" width="45px"></a>
<a href="https://github.com/Harrison0x80">
    <img src="https://avatars2.githubusercontent.com/u/8622915?s=400&v=4" width="45px"></a>

### 为何弄个2.0？
在2017年末的时候，偶然接触了Shiro这套安全框架，在学习完后萌发了自己搭建一套权限系统的想法，于是[FEBS-Shiro第一版](https://github.com/wuyouzhuguli/FEBS-Shiro/tree/mysql)
就诞生了。当时并没有太多考虑，所以前端框架选择了一套符合自己审美的单页框架。但单页的框架局限性较大，不适合企业应用，于是在第一版发布近一年半后，我突然又萌发了出个多标签页的2.0版本。

为何2.0前端选择LayUI？LayUI是一款优秀的国产前端框架，像Layer等组件非常契合国内后台系统的需求，所以LayUI成了我的不二之选。

其实写这段也是为了回复偶然看到的一个[评论](https://www.toutiao.com/a6704144784711221772/?tt_from=mobile_qq&utm_campaign=client_share&timestamp=1560960905&app=news_article&utm_source=mobile_qq&utm_medium=toutiao_android&req_id=201906200015050101520191684437A62&group_id=6704144784711221772)：

![](screenshot/comment.png)

不可否认的是，目前权限系统确实太多太多了，这套采用传统架构，没有使用Spring Cloud，没有使用Vue，React，前后端并没有分离的权限系统确实没有什么新鲜的地方。
但要做到美观易用的同时又支持多浏览器，多分辨率布局，要考量的东西还是不少。并且在前后端一套系统写下来的过程中，自己也能领会到一些东西。相信无论是学习Spring Boot，Shiro还是前端代码的封装，这套系统都能给你带来一定的帮助。

总之，开源并不是为了炫技，也不是为了获得额外收入，只是希望自己在学习的过程中也能帮助到一些人。还有我也不是什么高级工程师，只是一个名不见经传的小员工，开发这套系统也用不着3个月，
端午3天加一个周末足够了。

### 反馈交流
加入QQ群和大家一起~~交流~~吹水：

![qq](screenshot/QQ.jpg)
### 支持作者
如果该系统对您有帮助的话，请作者喝杯肥宅水吧🍺~

![treatme](screenshot/treatme.jpg)

