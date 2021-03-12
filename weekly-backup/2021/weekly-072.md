## 前言

WecTeam 前端周刊（<https://github.com/wecteam/weekly>）是由 WecTeam 维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 072 期发布时间：2021-03-12。

WecTeam（维C团）是京东旗下京喜事业群的前端技术团队，主要专注于前端工程化、Web 性能优化、小程序开发、Severless、多端复用、可视化搭建等前沿技术研究。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。


## 周刊文章

#### 1、[新兴前端框架 Svelte 从入门到原理](https://mp.weixin.qq.com/s/7GTTAYNf28IvIe2bpfVHuQ)
Svelte 作为新兴的前端框架，采用了和 React， Vue 不同的设计思路，其独特的特性在某些场景下还是很值得尝试的。

#### 2、[Flutter2重点更新一览](https://mp.weixin.qq.com/s/EzS3dtpZB_i9p358qqlBpg)
Google官方发布的Flutter2.0版本说明。1.Flutter web发布稳定版。2.对于PC端的支持。3.Dart更新2.12，支持null safe。4.多引擎内存优化。

#### 3、[iOS 稳定性问题治理：卡死崩溃监控原理及最佳实践](https://mp.weixin.qq.com/s/cEfIZGtUojKKbhIfUyhTMw)
不同于 Android 系统中的卡死（ANR）问题，目前业界对 iOS 系统中 App 发生的卡死崩溃问题并无成熟的解决方案，这篇文章介绍了字节跳动自研的一套专门用于定位生产环境中的卡死崩溃的解决方案。

## 经典文章

#### 1、[Webpack 基石 tapable 揭秘](https://mp.weixin.qq.com/s/9DJNBxS6PUWbngLZSDmzjQ)
Webpack 基于 tapable 构建了其复杂庞大的流程管理系统，基于 tapable 的架构不仅解耦了流程节点和流程的具体实现，还保证了 Webpack 强大的扩展能力；学习掌握tapable，有助于我们深入理解 Webpack。

#### 2、[【Webpack 进阶】Webpack 打包后的代码是怎样的？](https://juejin.cn/post/6937086236926410783)
webpack 打包后的代码是怎样的？是怎么将各个 bundle连接在一起？模块与模块之间的关系是怎么处理的？动态 import() 的时候又是怎样的？本文带我们一步步来揭开 webpack 打包后代码的神秘面纱。

#### 3、[浏览器缓存](https://juejin.cn/post/6844903763665240072)
浏览器缓存有很多优点，即能够减少数据传输减少网费，也能提示页面的加载速度。本文详细讲解了强缓存和协商缓存命中规则。读完之后可以思考我们自己对于前端资源的缓存策略，以及为什么要这样做。ck 打包后代码的神秘面纱。

#### 4、[在Web中实现表情符号的输入](https://segmentfault.com/a/1190000039359624)
本文介绍了如何在Web开发中实现支持表情符号的输入框。

#### 5、[一款可让大型iOS工程编译速度提升50%的工具](https://mp.weixin.qq.com/s/uBpkelG8q_xmskWPYyWONA)
本文介绍了美团平台自研的一款 cocoapods 插件 cocoapods-hmap-prebuilt，该插件以 Header Map 技术为基础，进一步提升代码的编译速度，完善头文件的搜索机制，通过该插件可以大幅提升 iOS 工程代码的编译速度。文章前半部分主要介绍相关的原理，后面主要阐述在工程层面的实践，希望能给从事相关开发的同学带来一些帮助或者启发。

#### 6、[今日头条品质优化 - 图文详情页秒开实践](https://mp.weixin.qq.com/s/Xqr6rQBbx7XPoBESEFuXJw)
h5页面的打开速度直接关系到用户使用的核心体验，本文介绍了对h5加载优化的思路和实践。

#### 7、[从预编译的角度理解Swift与Objective-C混编机制](https://mp.weixin.qq.com/s/gI9vL1KlHuMzMoWWf2tnIw)
1.介绍了预编译的基础知识。2.ObjC-Swift头文件是如何互相查找的。


## 资源文章

#### 1、[5个不常提及的HTML技巧](https://mp.weixin.qq.com/s/Sr6GwTdoQrMoyBZ5BWmo_g)
虽然HTML的使用很普遍，但还有很多的内容需要我们深入学习和实践，本文提供了5个不常见却还不错的HTML技巧。

#### 2、[dom-to-image原理](https://www.jianshu.com/p/1628d41ec1ff)
本文解析了开源库dom-to-image的基本原理，提供了一种以dom来将各种元素拼接成一张图片，这在分享和海报上有一定的应用场景。

#### 3、[XCode Templates tutorial &ndash; How to create custom template step by step](https://itcraftapps.com/blog/xcode-templates-tutorial/#whatisxcode)
将重复的工作任务使用模版化是一个非常好的方式，不仅能提供工作效率，也统一的各个模块的架构标准及代码的复用。特别在快速迭代的需求开发中，显得尤为重要。

#### 4、[西瓜视频稳定性治理体系建设一：Tailor 原理及实践](https://blog.csdn.net/bytedancetech/article/details/111189304)
Tailor是一款内存快照裁剪压缩工具，能高效裁剪压缩内存快照，应用到线上，对OOM、Crash等治理有很好的帮助。

#### 5、[带你全面了解 Flutter，它好在哪里？它的坑在哪里？ 应该怎么学？](https://juejin.cn/post/6932033252320346126)
本文作者有较为丰富的flutter开发经验，本文从Flutter优势、学习方式、目前Flutter的问题三个方面较为全面的介绍了flutter的现状。


