
# WecTeam 前端周刊：第 006 期

## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)（github.com/wecteam/weekly）是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 006 期发布时间：2019-10-11。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

#### 1、[换种方式读源码：如何实现一个简易版的Mocha](https://mp.weixin.qq.com/s/v90mFJ6YXdyj58zplxgKaA)

本文作者@**黄浩群**。Mocha 是目前最流行的 JavaScript 测试框架，理解 Mocha 的内部实现原理有助于我们更深入地了解和学习自动化测试。然而阅读源码一直是个让人望而生畏的过程，大量的高级写法经常是晦涩难懂，大量的边缘情况的处理也十分影响对核心代码的理解，以至于写一篇源码解析过后往往是连自己都看不懂。所以，这次我们不生啃 Mocha 源码，换个方式，从零开始一步步实现一个简易版的 Mocha。

#### 2、[Electron实践笔记](https://mp.weixin.qq.com/s/aa6LvpZRQQdrk_C-QxLXpg)

本文作者@**周全**。社交魔方平台是京东的 SNS 活动搭建平台，其内置了很多模板，每一个模板都有一个模板 JSON 用于生成表单，运营同学、商家配置了这个表单后就可以生成活动页面了。模板 JSON 是标准的结构化数据，包含名称、类型、控件类型、校验器、默认值等等字段。以往都是采用手写 JSON 的方式，这是非常低效的，而且容易出错。针对其结构化数据的特点可以用 GUI 的方式去编辑，我们基于 Electron 参考 Github Desktop 客户端 的架构编写了一个 JSON 编辑器，通过填写表单的方式生成 JSON。所以在这里记录下这个 Electron 编辑器开发过程中可以记录的点和从 Github Desktop 客户端代码中值得学习的点。


#### 3、[从零开始手写redux](https://mp.weixin.qq.com/s/XDVAN-GQcxlJvg8jjGqyLw)

跟随作者一步一步从零开始实现redux的重要功能，能充分了解redux的工作机制和实现原理，同时能够对自己从零实现开源库有一定的参考价值。

#### 4、[每日优鲜供应链前端团队微前端改造](https://juejin.im/post/5d7f702ce51d4561f777e258)

本文介绍了每日有限前端整合、重构的一些技术点以及技术细节。

#### 5、[Vue3 中的数据侦测](https://juejin.im/post/5d99be7c6fb9a04e1e7baa34)

这两篇文章从Vue最核心的响应式入手，解读Vue的源码，值得一看。

#### 6、[精读《用 Babel 创造自定义 JS 语法》](https://juejin.im/post/5d9be731f265da5bbc3e879b)

《用 Babel 创造自定义 JS 语法》这篇英文文章，最近在外网很火，有空不妨静下心来走一遍文章的思路。本文是对这篇外文的解读。

## 经典文章

无。

## 资源

#### [菜鸡到鸵鸟进阶之”用H5制作酷炫的视频播放器](https://blog.souche.com/cai-niao-dao-tuo-niao-jin-jie-zhi-yong-h5zhi-zuo-ku-xuan-de-shi-pin-bo-fang-qi-2/)

开发一个视频播放器。

#### [非常全面的前端协作规范](https://mp.weixin.qq.com/s/zpFkhAkpdE9dEg9t-FkPog)

万字长文的前端规范。

#### [第一类错误和第二类错误](https://mp.weixin.qq.com/s/uEJ6fIRR2GAsJsFPkDy_CQ)

第一次知道错误的分类。

#### [用惰性加载优化 React 程序[每日前端夜话0x6D]](https://mp.weixin.qq.com/s/ugKEMYnIp8neG0iCnuVdDQ)

惰性加载是一种优化 Web 应用和移动应用的旧技术。非常直截了当 —— 如果在某一时刻资源没有被查看或需要，就不要渲染它们。

#### [Webpack 热更新](https://juejin.im/post/5d8b755fe51d45781332e919)

Webpack热更新（ Hot Module Replacement，简称 HMR，后续均以 HMR 替代），无需完全刷新整个页面的同时，更新所有类型的模块，是 Webpack 提供的最有用的功能之一。

#### [Webpack 4 配置最佳实践](https://zhuanlan.zhihu.com/p/38456425)

Webpack 4 发布已经有一段时间了。Webpack 的版本号已经来到了 4.12.x。但因为 Webpack 官方还没有完成迁移指南，在文档层面上还有所欠缺，大部分人对升级 Webpack 还是一头雾水。以下是作者对迁移到 Webpack 4 的一些经验。

#### [一个便捷的文章发布平台](https://github.com/crawlab-team/artipub)

安利一款开源的一文多发平台，可以帮助文章作者将编写好的文章自动发布到掘金、SegmentFault、CSDN、知乎、开源中国等技术媒体平台，传播优质知识，获取最大的曝光度。ArtiPub安装简单，提供了多种安装方式，可以一键安装使用，安装一般只要5分钟。

## 废弃

#### [Vue 3 原理剖析：数据响应系统](https://juejin.im/post/5d996e3e6fb9a04e3043cc5b)

国庆期间前端最重磅的消息：Vue3.0的提前版源码在Vue_Lodon期间发布，几天时间已经出现好多vue3的文章了。这篇将会带着大家学习数据响应相关的内容，并且尽可能的脱离源码来了解原理，降低大家的学习难度。

#### [2020 年你应该知道的 8 种前端 JavaScript 趋势和工具](https://www.infoq.cn/article/VdJX0JkmSm_dkJBgF23r)

前端开发人员和技术人员的数量逐年增加，而整个生态系统渴望实现标准化。新技术和工具的出现已经改变了游戏规则。可以肯定地说，总体趋势将是 UI 标准化、基于组件的模块化和组合，这将影响从样式到测试甚至状态管理的所有方面，并在总体上实现更好的模块化。





