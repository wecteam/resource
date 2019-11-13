
# WecTeam 前端周刊：第 009 期

## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)（github.com/wecteam/weekly）是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 009 期发布时间：2019-11-01。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

#### 1、[【原创】手写一个四则运算表达式转换成AST的方法（下）](https://mp.weixin.qq.com/s/lHYZja_EFRl4s5UQH-kL3w)

本文作者@吴冠禧。[上篇](https://mp.weixin.qq.com/s/HMggcevKJ9afZFqHgm0e5A)我们利「用有限状态机」成功实现了「词法分析」，本篇将进入到「语法分析」及后续部分。

#### 2、[【原创】WebAssembly实战-在浏览器中使用ImageMagick](https://mp.weixin.qq.com/s/FiJYBjestHUk22z_nSYwrQ)

本文作者@刘辉。ImageMagick 是著名的 C/C++ 图形工具库，有命令行上的 `PhotoShop` 之称，支持包括 psd，ai 等超过 200 种格式图像的各种处理，本次我们把 `ImageMagick` 移植到前端，用它来在浏览器中完成各种图像处理操作。

#### 3、[现代浏览器观察者 Observer API 指南](https://juejin.im/post/5db10695e51d452a091fde90)

本文介绍了现代浏览器支持的四种不同类型的观察者（交叉观察者，变动观察者，视图观察者，性能观察者），这四个观察者，都非常适合集成到监控系统。

#### 4、[自动化 Web 性能分析之 Puppeteer 爬虫实践](https://juejin.im/post/5d90ca605188252ca056c44c)

Puppeteer 是一个 Node 库，它提供了一整套高级 API 来通过 DevTools 协议控制 Chromium 或 Chrome。正如其翻译为“操纵木偶的人”一样， 你可以通过 Puppeteer 的提供的 API 直接控制 Chrome，模拟大部分用户操作来进行 UI 测试或者作为爬虫访问页面来收集数据。

#### 5、[「前端进阶」高性能渲染十万条数据(虚拟列表)](https://juejin.im/post/5db684ddf265da4d495c40e5)

在工作中，有时会遇到需要一些不能使用分页方式来加载列表数据的业务情况，对于此，我们称这种列表叫做长列表。比如，在一些外汇交易系统中，前端会实时的展示用户的持仓情况(收益、亏损、手数等)，此时对于用户的持仓列表一般是不能分页的。

在高性能渲染十万条数据(时间分片)一文中，提到了可以使用时间分片的方式来对长列表进行渲染，但这种方式更适用于列表项的DOM结构十分简单的情况。本文会介绍使用虚拟列表的方式，来同时加载大量数据。

#### 6、[爱奇艺直播 WebAssembly 优化之路](https://mp.weixin.qq.com/s/LRGNOuFwHXALs_lhPyN3Zw)

在WebAssembly出现之前，JavaScript是浏览器里可以运行的唯一的编程语言。而WebAssembly技术使浏览器运行别的语言编写的程序变成了可能。
本篇文章是爱奇艺在WebAssembly上的实践总结。

#### 7、[面向传统，Serverless 进化之路](https://zhuanlan.zhihu.com/p/87940654)

主要讲述的是阿里集团内部逐步迁移到 Serverless 体系的过程以及思考，在 JSConf China 上做过分享。

#### 8、[Flutter在京东7FRESH的业务实践](https://mp.weixin.qq.com/s/N2W3u0Od7WgLretuE5T8RA)

讲述了京东7FRESH团队在他们业务中的Flutter实践，总结了期间遇到的一些问题以及对应的解决方案，最终向我们呈现了Flutter实践所达到的收益。

#### 9、[webpack 5 之持久化缓存指南](https://mp.weixin.qq.com/s/oB5eYax_NndcM5IinPgzNQ)

继 webpack v5-beta0 发布后，官方又发布了持久化缓存指南。

## 经典文章

#### [NodeJS与模块系统](https://mp.weixin.qq.com/s/uDp0v_1hN0Uzg-EGr1yfgA)

本文主要讲解nodejs模块的引入commonjs和es6两种规范，对比两种方式，着重介绍了node如何使用es6模块。

#### [JavaScript深入浅出第4课：V8引擎是如何工作的？](https://blog.fundebug.com/2019/07/16/how-does-v8-work/)

V8引擎是2008年发布的，它的命名灵感来自超级性能车的V8引擎，敢于这样命名确实需要一些实力，它性能确实一直在稳步提高，收获一众粉丝，就连浏览器界的独树一帜的Microsoft也投靠了Chromium阵营。

#### [Chrome 浏览器垃圾回收机制与内存泄漏分析](https://juejin.im/post/5db2beb8e51d455b450a64b4)

详细解析垃圾回收的几种机制，并举例一些常见的会导致内存泄漏的错误写法，实践意义较强。

#### [每个前端工程师都应该了解的图片知识](https://segmentfault.com/a/1190000019231550)

随着web的发展，网站资源的流量也变得越来越大。据统计，60% 的网站流量均来自网站图片，可见对图片合理优化可以大幅影响网站流量，减小带宽消耗和服务器压力。

#### [JavaScript 中的“黑话”](https://mp.weixin.qq.com/s/104zIj_qhh9TQP1f02XPhg)

那些 JavaScript 中容易不小心就被用滥的语法。

## 资源

#### [The Problems of Shared Mutable State and How to Avoid Them](https://2ality.com/2019/10/shared-mutable-state.html)

javascript进阶，共享可变状态问题以及如何避免。

#### [如何保障前端项目的代码质量](https://juejin.im/post/5b911f306fb9a05cdb1013b9)

对于中大型前端项目，项目规范与代码质量尤为重要。当功能需求变更或需要重构时，随心所欲的(糟糕的)代码可能带来比重新开发还麻烦的问题。

#### [Svelte vs React: 第一印象](https://medium.com/javascript-in-plain-english/svelte-vs-react-first-impression-1ce5d3ee6889)

Svelte 是一个用来构建Web应用的JS库。 Svelte 认为 virtual DOM 带来了额外开销，相比React和Vue它没有virtual DOM ，更像一个编译器。可以通过这篇文章大概了解Svelte3.0的优缺点。

#### [Vue 3.0前的 TypeScript 最佳入门实践](https://mp.weixin.qq.com/s/Zj-QXvAbd7yRnkUv_drHSw)

文章对TypeScript和当下Vue如何使用ts写法，做了一些简单的使用和介绍。

#### [基于 NodeJS 的 serverless 架构实践](https://mp.weixin.qq.com/s/rR8VK7RodyCofOiSehF6fA)

阿里官方解密：基于 NodeJS 的 Serverless 架构实践。


