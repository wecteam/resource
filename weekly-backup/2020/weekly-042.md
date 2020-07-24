## 前言

WecTeam 前端周刊（https://github.com/wecteam/weekly）是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 042 期发布时间：2020-07-17。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

#### 1、[【原创】如何实现一个圆弧倒计时进度条](https://mp.weixin.qq.com/s/f2ZhTN-5R6GOxrJDBrjcVQ)
本文作者@**郭世平**。最近的项目中，需要实现一个圆弧形倒计时进度条，对于本来 css 知识薄弱的我当场就懵逼，脑海里总是不断思考如何实现，不幸的是脑袋里没能蹦出半个想法。

#### 2、[救火必备！问题排查与系统优化手册](https://mp.weixin.qq.com/s/AYf-sUv2StODBx-10_K0Sg)

软件工程领域存在一个共识：维护代码所花费的时间要远多于写代码。而整个代码维护过程中，最惊心动魄与扣人心弦的部分，莫过于问题排查（Trouble-shooting）了。特别是那些需要 7x24 小时不间断维护在线业务的一线服务端程序员们，大大小小的问题排查线上救火早已成为家常便饭，一不小心可能就吃成了自助餐 —— 竖着进躺着出，吃不了也兜不住。本文分享作者在服务端问题排查方面的一些经验，包括常见问题、排查流程、排查工具，结合实际项目中发生过的惨痛案例进行现身说法。

#### 3、[精读《用 React 做按需渲染》](https://mp.weixin.qq.com/s/dEIL8aJedVjQl4Z8TsL6uQ)
介绍如何利用 DOM 判断组件在画布中是否可见这个技术方案，从架构设计与代码抽象的角度一步步分解。


## 经典

#### [还在看那些老掉牙的性能优化文章么？这些最新性能指标了解下](https://juejin.im/post/5f0b056de51d45349917bf16)
在实际工作中，如何量化性能优化也是相当重要的一环，本文主要介绍谷歌提倡的七个用户体验指标。

#### [现代浏览器内部机制 — 渲染进程的一生](https://mp.weixin.qq.com/s/RBQloSbupaDi6EuPpGLCbQ)
讲述浏览器到底是怎样工作的，一探渲染进程内部。

#### [玩转前端二进制](https://segmentfault.com/a/1190000023101367)
本文介绍了前端如何进行图片处理,然后穿插地介绍了二进制、Blob、Blob URL、Base64、Data URL、ArrayBuffer、TypedArray、DataView 和图片压缩相关的知识点。

#### [探索 React 内核：深入 Fiber 架构和协调算法](https://mp.weixin.qq.com/s/l2u4HAlmH6xudLa6qozWfw)
深度长文介绍 Fiber 架构和协调算法，配以丰富的图文、代码示例以及参考链接，有利于学习以及加深对react Fiber架构的理解。

#### [思想实验：如何在Vue中使localStorage具有响应式？](https://juejin.im/post/5f0d4c9be51d4534a5416a9c)
文章从Vue响应式与localStorage能不能一起使用这个问题出发，带领读者更好地了解Vue响应式在幕后的工作方式并充分利用这一点

#### [Vue Composition API 和 React Hooks 对比](https://mp.weixin.qq.com/s/tXwSFUz-ZDlP_dSp2Jevhg)
React Hook 底层是基于链表实现，调用的条件是每次组件被 render 的时候都会顺序执行所有的 Hooks。Vue Hook 只会被注册调用一次，Vue 能避开这些麻烦的问题，原因在于它对数据的响应是基于 proxy 的，对数据直接代理观察。

#### [serviceworker运用与实践](https://github.com/omnipotent-front-end/blog/issues/2)
先简单介绍前端常见的缓存方式，再引入serviceworker的概念，针对其原理和运用进行讨论


## 资源

#### [SpriteJS的3D渲染能力 Up, Up, Up!](https://zhuanlan.zhihu.com/p/103253115)
使用SpriteJS的3D扩展实现各种炫酷效果

#### [HTTP/2之服务器推送(Server Push)最佳实践](https://juejin.im/post/5b5935f76fb9a04f89783b44)
如果服务端接收到客户端主请求，能够“预测”主请求的依赖资源，在响应主请求的同时，主动并发推送依赖资源至客户端。客户端解析主请求响应后，可以”无延时”从本地缓存获取依赖资源, 减少访问延时, 提高访问体验，也加大了链路的并发能力。

#### [Nodejs进阶：crypto模块中你需要掌握的安全基础知识](https://mp.weixin.qq.com/s/2jiGRQx3EFK9ksm9kJUeTA)
nodejs使用crypto处理加解密的基础知识。可以通过本文，了解加解密常识，如：摘要，带秘钥摘要，对称加密和非对称加密的介绍，应用和伪代码使用，数字签名，分组加密等