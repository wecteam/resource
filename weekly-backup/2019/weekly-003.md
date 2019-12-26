
# WecTeam 前端周刊：第 003 期

## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)（github.com/wecteam/weekly）是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 003 期发布时间：2019-09-13。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

#### 1、[原创【译】在生产环境中使用原生JavaScript模块](https://mp.weixin.qq.com/s/aG-jA5mtvH7wO5NaMXVDwA)

本文作者@**龚亮**。打包生产代码一直是需要权衡利弊。一方面，希望代码尽快加载和执行。另一方面，又不希望加载用户实际用不到的代码。同时，还希望代码尽可能地被缓存。因此，找到最优打包粒度的挑战是在加载性能和长期缓存之间取得适当的平衡。

#### 2、[【原创】手把手教你写webpack loader](https://mp.weixin.qq.com/s/gTAq5K5pziPT4tmiGqw5_w)

本文作者@**黄浩群**。loader 和 plugins 是 webpack 系统的两大重要组成元素。依靠对 loader、plugins 的不同组合搭配，我们可以灵活定制出高度适配自身业务的打包构建流程。

#### 3、[JavaScript性能开销之2019](https://mp.weixin.qq.com/s/9djMvcl18hltRc2hN7aWDQ)

下载和执行时间是加载脚本节省性能开销的主要瓶颈，文章分析了前端性能的瓶颈以及优化思路。

#### 4、[灵活运用CSS开发技巧(66个实用技巧，值得收藏)](https://juejin.im/post/5d4d0ec651882549594e7293)

何为技巧，意指表现在文学、工艺、体育等方面的巧妙技能。代码作为一门现代高级工艺，推动着人类科学技术的发展，同时犹如文字一样承托着人类文化的进步。文章作者整理了三年来使用到的一些CSS开发技巧，希望能让读者写出耳目一新、容易理解、舒服自然的代码。

#### 5、[Node.js 的进程与线程你真的了如指掌了吗](https://mp.weixin.qq.com/s/5LHdvZu7zs9R0paOgz9yOQ)

本篇文章除了介绍概念，通过Node.js 的角度讲解进程与线程，并且讲解一些在项目中的实战的应用。

#### 6、[移动端滚动穿透的 6 种解决方案](https://mp.weixin.qq.com/s/3-M1wAtw6xYmsPlg768NOQ)

详细分析并总结了移动端弹窗滚动穿透的场景，总有一种能够解决你的问题。

#### 7、[时间切片（Time Slicing)](https://juejin.im/post/5ce249896fb9a07ea712e26e)

来看看听起来很高端的“时间切片”到底是什么。

#### 8、[小程序底层实现原理及一些思考](https://mp.weixin.qq.com/s/EbO7Wp6s29X9YliA2M-iCg)

本篇文章更多的是在描述架构与技术方向层面的思考和决策，不会过多介绍具体某个问题是如何解决的，因为细节实在太多。

#### 9、[Serverless For Frontend 前世今生](https://zhuanlan.zhihu.com/p/77095720)

阿里nodejs核心开发人员讲解severless的演进过程。

## 经典文章

#### [MVVM 框架的数据状态管理的发展与探索](https://github.com/farzer/blog/issues/1)

在前端应用日渐复杂的环境下，前端页面状态管理可控制和可跟踪成为解决开发和调试的重要手段，显然我们有必要了解状态管理方案可以解决什么问题，解决问题的核心方式是什么。

#### [一文搞懂浏览器缓存机制](https://mp.weixin.qq.com/s/rUbGSeIthEh0Fj-60j7Nzg)

在前端开发中，性能一直都是被大家所重视的一点，然而判断一个网站的性能最直观的就是看网页打开的速度。其中提高网页反应速度的一个方式就是使用缓存。一个优秀的缓存策略可以缩短网页请求资源的距离，减少延迟，并且由于缓存文件可以重复利用，还可以减少带宽，降低网络负荷。

#### [JavaScript Errors 指南](https://github.com/Jocs/jocs.github.io/issues/1)

捕获、报告、以及修改错误是维护和保持应用程序健康稳定运行的重要方面。由于Javascript代码主要是在客户端运行、客户端环境又包括了各种各样的浏览器。因此使得消除应用程序中 JS 错误变得相对困难。关于如何报告在不同浏览器中引起的 JS 错误依然也没有一个正式的规范。除此之外，浏览器在报告JS错误也有些bug，这些原因导致了消除应用程序中的JS 错误变得更加困难。这篇文章将会以以上问题作为出发点，分析JS错误的产生、JS错误包含哪些部分、怎么去捕获一个JS错误。

#### [web页面录屏实现](https://juejin.im/post/5c601e2f51882562d029d583)

有些时候，当你不知道用户的具体操作时，是没有办法重现某些bug的，这时候如果有操作录屏，你就可以清楚地了解到用户的操作路径，从而复现这个BUG并且修复。本文是针对该问题提供了一些实现思路。

#### [用React Hooks与Web Animation API实现动效组件](https://zhuanlan.zhihu.com/p/81954538)

「Web Animation API」W3C 推荐动画解决方案 与 「React Hooks」React  推荐编程模式结合是怎样的体验呢？如果你还没有尝试 WAAPI 及 React Hooks，那么看这篇就对了。

#### [Array 原型方法源码实现大解密](https://mp.weixin.qq.com/s/BM0W8KH20Vy_Jodt_LPQuw)

知其然知其所以然，本文深入讲解了数组方法的实现，值得一看。

## 资源

#### [如何使用CSS混合模式和SVG动态更改产品图像的颜色](https://tympanus.net/codrops/2019/09/03/how-to-dynamically-change-the-colors-of-product-images-using-css-blend-mode-and-svg/)

本文介绍一种简单的方式，利用 SVG 和 CSS 混合模式动态替换产品图片颜色。

理由：待翻译。

#### [Google feedback on TypeScript 3.5](https://github.com/microsoft/TypeScript/issues/33272)

Google升级到ts-v3.5的建议反馈。

理由：待翻译。

## 废弃

#### [JavaScript 之 import export Vs require module.exports](https://www.jeffjade.com/2019/08/28/159-js-import-export-vs-require-module-exports/)

本篇文章，旨在探讨 JavaScript 模块化体系中：ES6 模块与 CommonJS 模块的差异，以及各自用法注意事项等。

理由：上一期周刊中，有一篇更好的文章讲过这个话题。

#### [MTFlexbox自动化埋点探索](https://zhuanlan.zhihu.com/p/78412889)

本文主要介绍美团在MTFlexbox自动化埋点方向所进行的一些探索，希望对大家能够有所帮助。

理由：现在都是标准化的了。非标准化的过时了。

#### [实用函数式编程技巧：Combinator Pattern](https://mp.weixin.qq.com/s/zGE4lirhsdR2BJV86RJWpA)

推荐人@志玉。本文以中间展开渐进式呈现图片的算法为例。演示Combinator Pattern 可以如何呈现出优雅的计算层次结构。

理由：文章内容，没体现出作用。

#### [【原创】不懂不写系列：JavaScript的异步机制，EventLoop，macrotask，microtask，nextTick终结篇](http://kai.ge/posts/%E4%B8%8D%E6%87%82%E4%B8%8D%E5%86%99%E7%B3%BB%E5%88%97macrotask%E5%92%8Cmicrotask%E7%BB%88%E7%BB%93%E7%89%88/)

本文作者@郑凯。涉及到了JavaScript的异步机制的来龙去脉，可以串联起来大量知识，既是基础也是核心。

理由：等待发公号原创。

#### [小程序底层实现原理及一些思考](https://github.com/berwin/Blog/issues/43)

小程序是近年来最火热的前端技术之一，然而即使知道如何开发小程序，对于大部分前端开发者来说小程序内部依然是一个黑盒，本文带你了解一下小程序的底层是如何实现的。

理由：重复推荐。

