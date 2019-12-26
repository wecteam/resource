
# WecTeam 前端周刊：第 005 期

## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)（github.com/wecteam/weekly）是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 005 期发布时间：2019-09-27。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

#### 1、[【原创】你还在用图片做引导蒙层？](https://mp.weixin.qq.com/s/XotuXv-EPv-VLNHJ6r7htg)

本文作者@**罗文林**。本文讲述六种思路来实现引导蒙层，在一定情况下都能满足业务需求，从不同角度来实现了引导蒙层。z-index最简单，canvas最灵活，就个人而言，更加喜欢骨架屏式的动态opacity蒙层实现，更有趣更酷。

#### 2、[【原创】前端资源治理（一）:问题及思路](https://mp.weixin.qq.com/s/7kOscvap3bBR-tTJM8ckPA)

本文作者@**李刚松**。笔者对“前端资源治理”的定义是：将前端相关的页面、js/css/图片/字体、接口、配置、监控点等的依赖关系进行收集、存储和管理，并将割裂的组件系统、配置系统、监控系统、业务系统等进行重构和整合，最终形成以页面管理为基础的统一的有序的平台，所有关联信息都能够被查询和检索，最终实现整体协作效率的提升。

#### 3、[【原创】记一次Node.js直出服务的性能优化](https://mp.weixin.qq.com/s/knx_YeT0_Pv8ffV-gN9r9Q)

本文作者@**肖睦群、李刚松**。MPM（Market Page Maker）是京东社交电商部的组件化的页面可视化搭建平台，于2016年9月份上线，平均每周150+个页面，目前已经成为社交电商部的一个核心系统。系统使用Vue.js作为组件化的基础框架,并于2017年5月份上线了Node.js直出服务。

由于很多告警问题主要是流量暴涨导致的CPU使用率过大，我们本次重点优化服务的CPU消耗性能。分析CPU消耗的方法有多种,我们选择其中操作比较简单的v8-profiler方案：安装NPM包v8-profiler，在直出服务中添加监控代码，打包发布到预发布环境进行压测，收集监控数据再进行分析。

#### 4、[深入浅出动画帧后，我再也不怕动画了](https://mp.weixin.qq.com/s/D-Nd6fAp-X0mjqYwoU0hKg)

在前端性能优化策略中，耳熟能详的手段有，雅虎 35 条军规，使用 cache，减少请求数量，使用cookie-free domain，critical asset，使用 CDN，Lazy load，PreLoad 等，这些手段其实主要都是围绕怎么样更快的拿到所需关键资源。当我们把这一步做到很好，没有可优化空间了，其实还可以从另外一个方向去做优化，那就是浏览器渲染方面。文章从动画帧角度，描述了怎么样做一些优化工作。

#### 5、[JS+Canvas 带你体验「偶消奇不消」的智商挑战](https://segmentfault.com/a/1190000020268623)

canvas实现的最强大脑小游戏了解一下。

#### 6、[Nuxt 自适应 SSR 方案: SEO 和首屏最小化优化](https://juejin.im/post/5d87433151882548e51f8b46)

什么才是完美的SSR？一方面是页面的SEO优化，另一方面是对于用户体验的极致追求，要达到更好的SEO就得直出整个页面，而要让用户获得更优质的浏览体验就得务求精确的首屏直出，两者似乎不可调和。如何在这两者间取得平衡，本文提供了一个有趣的思路。

#### 7、[设计与算法 | Google Photos Web UI](https://mp.weixin.qq.com/s/XZw5yI_PBcD7VXO0NxnyNw)

详细阐述了Google Photos的照片布局实现过程，追求极致体验的交互与设计提现的淋漓尽致。

#### 8、[打破框架的范式之争](https://mp.weixin.qq.com/s/0YuYBqD2qWf_EgKMbow1dw)

这篇文章是工业聚大佬在 9.17 的 Github 首次粉丝见面会上演讲内容的文字稿，有兴趣的可以一读。

#### 9、[Vue性能提升之Object.freeze()](https://juejin.im/post/5d5e89aee51d453bdb1d9b61)

Object.freeze()可以冻结一个对象，如果你有一个巨大的数组或Object，并且确信数据不会修改，使用Object.freeze()可以让性能大幅提升。

## 经典文章

#### [关于移动端适配，你必须要知道的](https://mp.weixin.qq.com/s/V3UpVZH8AWfSScIRAsr2dw)

文章从移动端适配的基础概念出发，探究移动端适配各种问题的解决方案和实现原理。

#### [你了解vue3.0响应式数据怎么实现吗？](https://juejin.im/post/5cf8b51ae51d45590a445b0d)

本文讲解了vue3.0响应式数据怎么实现。

#### [论如何复用一个组件的逻辑](https://juejin.im/post/5d872f2df265da03dd3daf26)

本文简要地探讨了React和Vue两个主流视图库的逻辑组合与复用模式历史: 从最初的Mixins到HOC, 再到Render Props，最后是最新推出的Hooks。

#### [Visual Studio Code有哪些工程方面的亮点](https://zhuanlan.zhihu.com/p/35303567)

深入了解一下前端同学使用的工具。

#### [透过现象看本质: 常见的前端架构风格和案例](https://juejin.im/post/5d7ffad551882545ff173083)

详细的案例剖析解释了流行技术栈背后的架构思想，丰富的架构风格介绍让架构风格思路更加简洁同时也更具深度。

#### [90行代码，15个元素实现无限滚动](https://juejin.im/post/5d7f80796fb9a06b24434d4e)

解锁IntersectionObserver的更多玩法。

#### [说说JS中的沙箱](https://segmentfault.com/a/1190000020463234)

其实在前端编码中，或多或少都会接触到沙箱，可能天真善良的你没有留意到，又可能，你还并不知道它的真正用途，学会使用沙箱，可以避免潜在的代码注入以及未知的安全问题。

#### [随机不只是Math.random —— 前端噪声应用](https://juejin.im/post/5d285648f265da1b942176d8)

在了解噪声之前，很多人对随机的认识，仅仅停留在Math.random 。它很有用，比如H5 里的简单抽奖程序，或者随机选取一张卡片。而最近工作中需要实现一些的随机图像效果，让我发现这个函数能做的事十分有限。之后我偶然了解到噪声这一种随机形式，它很完美的解决了我的问题。

#### [基于 Vue 和 TS 的Web移动端项目实战心得](https://juejin.im/post/5d759f706fb9a06afa32adec)

移动端 Web 最佳实践，基于vue-cli3搭建的typescript 项目，可以用于 hybrid 应用或者纯 webapp 开发。

## 资源

#### [【原创】Electron实践笔记 - 开发魔方配置可视化](http://wqadmin.jd.com/webstatic/blogs/2019/09/24/electron-in-action/)

本文作者@周全。目前请在内网查看。为解决之前魔方手写JSON配置文件低效难用的问题，自己用Electron手撸一个工具。

#### [各ES版本的JavaScript特性清单](https://github.com/daumann/ECMAScript-new-features-list)

各ES版本的JavaScript特性清单，作为资源收藏。

#### [TypeScript手册最终版](https://zhuanlan.zhihu.com/p/82877006)

TypeScript 是人们最想学习的语言之一，这篇是Typescript的入门手册，随时查询。

#### [Wikipedia的代码瘦身](https://phabricator.wikimedia.org/phame/live/7/post/175/wikipedia_s_javascript_initialisation_on_a_budget/)

为了性能，wikipedia把JS代码缩减到28KB，这篇文章介绍他们是怎么做到的。

## 废弃

#### [“努力就会成功”](https://coolshell.cn/articles/19271.html)

来自技术圈大佬的文章，关于技术之外的思考。

#### [Litho 在动态化方案 MTFlexbox 中的实践](https://zhuanlan.zhihu.com/p/83886000)

MTFlexbox是美团内部应用的非常成熟的一种跨平台动态化解决方案，本文主要介绍在MTFlexbox中使用Litho优化性能的实践经验。
