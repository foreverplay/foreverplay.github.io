# 个人信息
 - 彭雷/男/1993
 - 本科/北京理工大学珠海学院
 - 工作年限：3年
 - Github：http://github.com/foreverplay
 - 期望职位：Web前端程序员
 - 期望薪资：税前月薪15k~20k，特别喜欢的公司可例外
 - 手机：17605099789
- Email：penglei4work@gmail.com
- QQ号：1032733313

# 工作经历
## 厦门优他动漫有限公司 （ 2016年7月 ~ 2018年3月 ）
### MUTA H5版
2016年我开始进行虚拟歌姬系统[MUTA H5版](http://star-fans.com/app/dist/)。作为项目的负责人，除完成了UI界面外、还采用localStorage技术对于用户的临时数据进行缓存、改写上拉加载组件、根据每句歌词拥有不同背景，设计了无jQuery依赖的图片播放器，并且集成了弹幕播放器方便B站的小伙伴无缝迁移、引入了canvas对用户上传图片进行裁剪。
项目运行一年半，最终在MUTA2.0版本以原生重写结束了H5版大部分功能，只保留H5版分享页面。其中图片播放器基于H5版原理实现，其余功能设计也是仿照H5版本实现。
最困难的问题是：因为是异步获取音频源，然后对audio标签的src赋值，但是出现了部分Android手机微信浏览器不能播放的问题。经过不断的尝试，最终通过研究audiojs的demo源码，在对audio的src标签赋值之后执行已废弃的load()解决问题。
最自豪的技术细节：用户选中某一行歌词并且配置图片之后，会在当前歌词行出现上下两个指针，滑动仁义指针会复制当前行的图片到其他歌词上。为了减少请求，操作会在本地进行合并，并且对指针停留的位置加大了判断区减少操作失误的可能性，方便用户操作。产品经理评价此设计具有原生应用般顺滑流畅。

### MUTA APP后台项目
后台项目由一个实习生用vue+element搭建，我负责指导帮助，必要时开发较复杂表单管理；还有一个利用长连接的聊天功能（扒微信网页版UI和基本逻辑）。最自豪的技术细节就是聊天功能，我对请求时间间隔进行了合理的设置，并且在组件destroyed状态之后关闭不必要请求。
之后MUTA APP升级2.0，后台提出大量不同需求，于是我使用create-react-app+ant design为基础框架，实现了新版后台需求，不过由于需求杂度一般，所以最大的难题倒是在于开始接触ant design时，create-react-app模板不能正常运行。最后根据issue提示，将create-react-app默认模板手动添加antd design组件。

### 其他项目
在职期间也进行了一些运营活动页面以及使用视差滚动技术的[公司官网](http://ai-muta.com/)开发、react实现的类似朋友圈社区、也用react实现spa版MUTA H5应用（练手项目，因为线上已经被原生取代）。期间大幅提升UI设计理念实现的能力；对[层叠水平（stacking level)](http://star-fans.com/app/dist/activity.html)和[触发BFC](http://star-fans.com/app/dist/fame.html)有过深入研究和大量实践；编写过gulp自定义任务；live2d网页版的集成；

## 沈阳乐见科技有限责任公司 （ 2015年7月 ~ 2016年7月 ）

### 公司官网
我在此项目负责整个[网站](http://www.lejaer.com/)的开发，采用canvas作为导航动画实施，并且大量使用css3动画的企业网站。首屏加载优化使用canvas作loading动画缓解等待时间。最大的困难在于canvas绘制与鼠标监听事件重叠导致的浏览器绘制性能问题，最后采用适当屏蔽鼠标监听事件解决。一些小困难在于pc端和手机端使用同一套html结构，为适配不同端，不得不对一些次要功能做了舍弃，以最大程度还原ui的设计理念。

### 炎黄玉官网
我所做的第一个网站项目，因为之前是做jQuery组件开发的，所以第一次接触css3动画，但是也只用了一天就完成的整体网站的展示页面和动画效果。虽然现在看来没有什么技术含量，但是它顺利的开启了我对前端的兴趣大门。

### 其他项目
因为公司属于创业型公司，所以在职期间完成了基于php的后台管理系统，微信公众号php服务端开发（如微信支付），多个响应式企业官网，微信H5推广页，hybird App开发等前端开发任务。同时也参与数据库设计及业务流程梳理等工作。
期间也学会了Photoshop必备切图技能。对网站SEO优化有一定的了解。

## 深圳华龙讯达信息技术股份有限公司 （实习：2014年12月 ~ 2015年6月 ）

我主要进行jQuery组件开发，工作中总能根据进度表提前完成分配任务，并且能够为同组成员提供一些有价值的帮助。

# 技能清单
以下均为我熟练使用的技能
- Web开发：html5/css3/javascript/babel ES6/jQuery/php
- Web框架：nginx
- 前端框架：Bootstrap/React/Vue
- 前端工具：Bower/Gulp/webpack
- 数据库相关：MySQL
- 版本管理：Svn/Git
- 云和开放平台：微信应用平台开发
- 抓包工具：Fiddler/Charles
- 相关效率工具：postman/sublime text/SSR/iMac

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
