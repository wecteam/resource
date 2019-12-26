
# WecTeam 前端周刊：第 010 期

## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)（github.com/wecteam/weekly）是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 010 期发布时间：2019-11-08。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

#### 1、[【原创】小程序工程化探索](https://mp.weixin.qq.com/s/_NSJTQ-4-8gTnwTVK-tn0A)

本文作者@**陈晓强**。小程序是近两年兴起的最热门的技术之一了，但不同于 H5 在工程化方面的成熟，小程序在工程化方面的探讨并不多。京东社交电商前端团队是最早的那一批小程序开发人员，有多早呢，我想可以用内测玩家这个词来形容。两年多以来，我们在工程化方面做了很多积累：包括规范化、组件化、工具化、自动化测试、持续集成系统等

#### 2、[【译】V8 引擎和 JavaScript 优化建议](https://mp.weixin.qq.com/s/W6y_C0SzrFph7o59WIwUzQ)

本文作者@**马雪琴**。V8 是谷歌用于编译 JavaScript 的引擎，Firefox 同样也有一个，叫 SpiderMonkey，它和 V8 有一些不同，但总体颇为相似。我们将在本篇文章中讨论 V8。

#### 3、[【原创】你应该知道的折叠屏手机适配](https://mp.weixin.qq.com/s/FKHZeT2zZgn4SrEvxrxINA)

本文作者@**龙朝忠**。随着三星 Galaxy Fold 和华为 Mate X 的发布，前端同学将面临一个新的任务：折叠屏的适配。折叠屏虽距离普及可能还有很长一段路，大多数公司还未将折叠屏列入适配的范围，但是提前研究下折叠屏的适配还是极好的。

因此对于我们开发同学来说，对折叠屏的适配首先要确定一个预期，即要先确定好交互和设计，才能评估工作。因此“折叠屏的适配先是一个设计问题，然后才是一个适配问题”。

#### 4、[Web 性能优化、文档及代码编辑器相关的新提案](https://mp.weixin.qq.com/s/OnTyKDIDIOcMJ5ZDhydYIQ)

关于Monaco Editor的提案。

#### 5、[腾讯视频Node.js服务是如何支撑国庆阅兵直播高并发的？](https://mp.weixin.qq.com/s/WKhALCAarFNOCQylBUryfQ)

本文从服务可用性、缓存、日志三个维度总结视频侧开发高并发Nodejs服务的一些经验。

#### 6、[万字长文总结前端测试体系建设与最佳实践](https://mp.weixin.qq.com/s/4oxdWm_wg59riJD4RBE_zg)

这篇文章主要总结了作者在 React 项目中书写测试的经验与沉淀。

#### 7、[2019年，你是否可以抛弃 CSS 预处理器？](https://aotu.io/notes/2019/10/29/css-preprocessor/)

前端的技术栈发展突飞猛进，W3C 的 CSS 工作组也一直在持续从社区汲取营养，加快 CSS 的迭代。那么到现在为止，CSS 是否可以取代 CSS 预处理器的地位？CSS 预处理器会不会成为 CSS 过渡时期的产物呢？

#### 8、[玉伯-我的前端成长之路](https://www.yuque.com/yubo/morning/grow-up-at-alibaba)

玉伯在阿里内部前端大学的一个分享，对在阿里的 11 年前端工作的一个总结分享。三个关键词：全情投入、守正出奇、愿等花开。

#### 9、[React Concurrent 模式抢先预览: useTransition 的平行世界](https://juejin.im/entry/5db65f80518825647313b0d8)

2019.10.24, 在 React Conf 2019 首日， React 官方正式发布了关于 Concurrent 模式的第一个早期社区预览文档, 正式和 React 的大众开发者见面, 令人兴奋。另外还有下篇：[React Concurrent 模式抢先预览下篇: useTransition 的平行世界](https://juejin.im/post/5dbee8e7e51d4558040f0830)

## 经典文章

#### [JavaScript手写代码无敌秘籍](https://juejin.im/post/5c9c3989e51d454e3a3902b6)

手写实现new操作符、JSON.stringify、JSON.parse、call、apply、bind、继承、Promise、Debouncing、Throttling、深拷贝、instanceOf，有助于我们更好的理解、使用这些功能。

#### [[译] JavaScript 工作原理：渲染引擎及其性能优化](https://juejin.im/post/5dbfdf0cf265da4cf376865e)

先介绍了浏览器的基本工作原理，然后给出了从各方面优化性能的方案。

#### [Nodejs中更快的async](https://mp.weixin.qq.com/s/5HDsrx-ElTS38NPGdeA9eQ)

异步函数是一个使用隐式Promise异步操作以返回其结果的函数。异步函数旨在使异步代码看起来像同步代码，为开发者隐藏异步处理的一些复杂性，使开发者用起来语法简洁清晰，可以直接用trycatch进行异常处理。但是在我们关注于异步函数开发调试遍历方面时，我们对他的性能演进可能并不是那么关注，本文介绍了V8对于异步函数的性能优化过程。

#### [H5秒开方案大全](http://www.alloyteam.com/2019/10/h5-performance-optimize/)

本文列举和总结偏向与客户端结合的hybrid秒开方案，以及部分提及纯前端秒开方案。

#### [响应至上：打造无卡顿的滚动列表](https://fed.taobao.org/blog/2019/09/02/make-infinite-scroll/)

在技术变化与发展如此之快的今天，web用户对页面的访问速度与响应度提出了越来越高的要求。其中的“响应度”不仅仅是实现层面的问题，更是个设计问题，仅靠性能优化与更快的硬件是难以解决的。

本文以常见的「无尽滚动列表」场景为案例，阐述如何从交互的角度看待和提升用户体验的思路，提升页面的「响应度」。

#### [实施前端微服务化的六七种方式](https://mp.weixin.qq.com/s?__biz=MjM5Mjg4NDMwMA==&mid=2652975949&idx=1&sn=c36387188283dd4fae52257357541729)

微前端架构是一种类似于微服务的架构，它将微服务的理念应用于浏览器端，即将 Web 应用由单一的单体应用转变为多个小型前端应用聚合为一的应用。

#### [鲜为人知的JavaScript陷阱](https://mp.weixin.qq.com/s/d9Za9IxtBxa5s-wEk0KsUQ)

虽说更多新功能可以让我们编写可读性和质量更高的代码，但我们也很容易被这些新奇、亮眼的特性迷惑，反而陷入一些潜在的陷阱。

## 资源

#### [React推出并发模式：可中断渲染、指定加载顺序、并行处理多状态](https://mp.weixin.qq.com/s/dYnARPfMptj1-iHL9HAjug)

并发模式是一组新功能，可以帮助 React 应用程序保持响应状态，并适当调整用户的设备功能和网络速度。

这些功能仍处于实验阶段，未来可能会发生更改。它们还不是稳定的 React 版本的一部分，但你可以在实验版本中尝试它们。

#### [实现图片懒加载的几种方案比较](https://juejin.im/post/5dbf7b6a6fb9a0207326b32b)

关于图片懒加载的实现思路以及优化。

#### [富文本原理了解一下？（一篇文章彻底搞定富文本原理 + 实战）](https://juejin.im/post/5cfe4e8a6fb9a07ec63b09a4)

让我们抓紧时间做一个属于自己的富文本吧，大概会包含以下几个功能：加粗、段落、H1、水平线、无序列表、插入链接、插入图片、后退一步、向前一步等等。Let's do it!

#### [9个项目助你在2020年成为前端大神](https://juejin.im/post/5dc0c744e51d456e7e41f5ac)

本文收集了9个使用了不同JS框架/库的项目，你可以去构建或者将他们加入到自己未来的开发计划中。记住，没什么比实际开发一个项目更有帮助。所以，不要犹豫，试着去开发一下。

#### [在 forEach 中使用 async/await 遇到的问题](https://togoblog.cn/javascript-async-await-in-foreach/)

是否真的了解forEach的内部逻辑？

#### [将 React 渲染到嵌入式液晶屏](https://juejin.im/post/5dbb729e51882524c101ffe1)

如何才能在浏览器之外，甚至在 Node.js 之外，用 React 渲染 UI 呢？本文将带你用 React 直通嵌入式驱动层，让现代前端技术与古老的硬件无缝结合。

## 废弃

#### [antd快速开发（Form篇）](https://mp.weixin.qq.com/s/mbLbI8gC_nlAlr7rkfnrAA)

antd的form组件在大规模使用时，并不优雅，需要大量的重复代码。通过封装，使用配置管理就方便很多。

