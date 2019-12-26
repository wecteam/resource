# WecTeam 前端周刊：第 004 期

## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)（github.com/wecteam/weekly）是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 004 期发布时间：2019-09-20。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

#### 1、[原创[译]Web内容如何影响电池的使用](https://mp.weixin.qq.com/s/OY2iiPyUe4calxyfxTlSKg)

翻译@刘辉。现在用户上网大多使用移动设备或者笔记本电脑。对这两者来说，电池寿命都很重要。在这篇文章里，我们将讨论影响电池寿命的因素，以及作为一个web开发者，我们如何让网页耗电更少，以便用户有更多时间来关注我们的内容。

#### 2、[V8 最佳实践：从 JavaScript 变量使用姿势说起](https://juejin.im/post/5d81a06ee51d4561ba48fea2)

在弱类型语言 JavaScript 中，变量上能有多少优化窍门？本文从最基础的变量类型说起，带你深入 V8 底层类型变换与优化机制。真正的老司机，一行代码可见一斑。以后你可以说，我写的代码，连变量声明都比你快。

#### 3、[[译]Uglify vs Babel-minify vs Terser 一场代码压缩的pk](https://juejin.im/post/5d6cd666e51d4561cb5ddee6)

线上js代码没有不压缩的，谁才是最好的压缩器？老牌的uglify?伴随babel崛起的babel-minify?还是新贵terser？

#### 4、[SVG Path路径在网页开发的作用](https://juejin.im/post/5b263f886fb9a00e63252dbe)

SVG是矢量图形表示，它的一个强大之处在于path标签可以表示任意的矢量形状，利用好这个path可以做出很多传统html/css做不出来的效果。

#### 5、[「前端进阶」高性能渲染十万条数据(时间分片)]( https://mp.weixin.qq.com/s/-UHOsR26jnnogHqPfPM0rQ)

一个展示时间分片不错的例子，如何优雅的渲染大量dom节点，但如何运用到小程序中是个值得思考的问题。

#### 6、[浏览器的一些“滚动”行为鉴赏](https://juejin.im/post/5d75adfbe51d4561e84fcc9c)

这篇文章主要聊聊滚动相关的一些方法跟属性，还有一些有趣的例子。

#### 7、[是谁，在敲打我窗-CSS雨滴动画效果](https://zhuanlan.zhihu.com/p/80852343)

纯css实现有趣的雨滴动画效果。

## 经典文章

#### [从Chrome源码看事件循环](https://zhuanlan.zhihu.com/p/48522249)

通过解读 chrome 源码和一些案例调试，帮助我们深入理解事件循环。

#### [浏览器垃圾回收机制与 Vue 项目内存泄漏场景分析](https://mp.weixin.qq.com/s/sMV4KyUb6RORJ4la7MfC4Q)

开发过程中可能遇到程序突然卡死或程序出现异常，这时我们就要对该 JS 程序进行内存泄漏的排查，该文章详细解析了浏览器内存机制和各种可能出现的异常场景，介绍了浏览器的垃圾回收机制以及vue项目的内存分析。

#### [深入理解ESLint](https://mp.weixin.qq.com/s/X2gShxrCw0ukZigjE_45kA)

ESLint 号称下一代的 JS Linter 工具，它的灵感来源于 PHP Linter，将源代码解析成 AST，然后检测 AST 来判断代码是否符合规则。ESLint 使用 esprima 将源代码解析吃成 AST，然后你就可以使用任意规则来检测 AST 是否符合预期，这也是 ESLint 高可扩展性的原因。

#### [HTTP请求之gzip压缩知多少](https://segmentfault.com/a/1190000020386580)

本文介绍gzip压缩原理以及使用方法。

#### [京东PLUS会员项目前端性能优化实践](https://juejin.im/entry/5c6613ed518825629d075478)

webpack4、Babel7、按需加载、骨架屏、PWA等最新的前端性能优化方案。

#### [如何编写高质量的函数-- 敲山震虎篇](https://juejin.im/post/5c6bbf0f6fb9a049ba4224fd#heading-19)

本文从函数的执行机制、鲁棒性、函数式编程、设计模式等方面，全面阐述如何编写高质量的函数。

#### [事件循环和异步更新](https://juejin.im/post/5d7e30dbf265da03cd0aaef4)

Vue和React都实现了异步更新策略。虽然实现的方式不尽相同，但都达到了减少DOM操作、避免过度渲染的目的。本文基于Event Loop机制，对Vue的异步更新策略作探讨。

#### [从多线程到Event Loop全面梳理](https://juejin.im/post/5d5b4c2df265da03dd3d73e5)

本文从浏览器进程、线程角度出发，对Event Loop进行全面梳理。

## 资源

#### [GitHub Actions 入门教程](http://www.ruanyifeng.com/blog/2019/09/getting-started-with-github-actions.html)

如何使用 GitHub Actions 自动发布一个 React 应用到GitHub Pages。

#### [JS 函数式编程指南](https://llh911001.gitbooks.io/mostly-adequate-guide-chinese/content/)

这是一本书，讲述了如何使用 Javascript 学习函数范式，作为函数式编程的学习资料再好不过了。

#### [Node.js 最佳实践](https://github.com/goldbergyoni/nodebestpractices/blob/master/README.chinese.md)

汇集了nodeJS结构设计，异常处理，编码风格等各个方面的优良实践方案！

#### [前端团队代码评审 CheckList 清单](https://juejin.im/post/5d1c6550518825330a3bfa01)

列举了很多不规范甚至错误的反面例子，但是在日常开发中，充斥着大量的这些熟悉的、亲切的代码。

#### [ES2018新特性——每个JS开发者都需要了解](https://www.zcfy.cc/article/new-es2018-features-every-javascript-developer-should-know)

ES2016、ES2017都用上了，是时候了解ES2018了。

## 废弃

#### [大规模应用 TypeScript](https://juejin.im/post/5d591d8a6fb9a06aee362f29)

现如下，TypeScript 已然兴起，如果各位小伙伴你们公司还未将开发迁移到 TypeScript 下，亦或正在迁移或者已经迁移了，那么不妨一起透过本文来看看 Airbnb 是如何做到大规模应用 TypeScript 的。

#### [Serverless 的喧哗与骚动](https://mp.weixin.qq.com/s/Uk7safZuPaDA9CefmRI9Fg)

Serverless 这个领域看起来极其美好，一旦深入去做了才发现实际非常复杂。本文作者将利用自身多年的研发经验，带领我们深入了解 Serverless 行业的发展！

#### [JavaScript 之 import export Vs require module.exports](https://www.jeffjade.com/2019/08/28/159-js-import-export-vs-require-module-exports/)

本篇文章，旨在探讨 JavaScript 模块化体系中：ES6 模块与 CommonJS 模块的差异，以及各自用法注意事项等。

