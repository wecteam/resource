
# WecTeam 前端周刊：第 002 期

## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 002 期发布时间：2019-09-06。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

#### 1、[【原创】Javascript抽象语法树上篇(基础篇)](https://mp.weixin.qq.com/s/Ri7DJVJa2ELFfxIRifs3tQ)

本文作者@**陈晓强**。日常工作中，我们会碰到js代码解析的场景，比如分析代码中 require 了哪些包，有些什么关键API调用，大部分情况使用正则表达式来处理，可一旦场景复杂，或者依赖于代码上下文时，正则就很难处理了，这时候就要用到抽象语法树。常见的 uglify、eslint、babel、webpack 等等都是基于抽象语法树来处理的，如此强大，有必要好好了解一下。

#### 2、[【原创】Javascript抽象语法树下篇(实践篇)](https://mp.weixin.qq.com/s/Fz9H5dscj5Oy__daecAYvg)

本文作者@**陈晓强**。本篇介绍AST的运用。AST应用的三个要点：

（1）需要一个解析器，将代码转换为AST。

（2）需要一个遍历器，能够遍历AST,并能够方便的对AST节点进行增删改查等操作。

（3）需要一个代码生成器，能够将AST转换为代码。

#### 3、[京东PC 首页2019 改版前端总结](https://aotu.io/notes/2019/08/26/jdindex_2019/index.html)

京东 PC 首页距离上次改版，已有2年3个月零五天。这次改版在延续17版的框架与流程的基础之上，为首页的稳定性、安全性、视觉体验、无障碍体验方面见缝插针地添了砖加了瓦。

#### 4、[伊斯坦布尔测试覆盖率的实现原理](http://www.alloyteam.com/2019/07/13481/)

单元测试无疑是一种衡量代码质量的重要手段，而测试覆盖率则是衡量测试完整性的一种手段，Istanbul 是一个基于 JavaScript 的测试覆盖率统计工具，目前被绝大多数测试框架使用。本文简单介绍其实现原理。

#### 5、[利用peerjs轻松玩转webrtc](https://www.cnblogs.com/yjmyzz/p/peerjs-tutorial.html)

非常值得一看的技术落地文章，框架上手简单明了，但如何将合适技术落地到业务中，创新更多玩法，是个值得思考的问题。

#### 6、[再看2019大前端技术趋势，Web OS概念正落地](https://developer.aliyun.com/article/711504)

前端三大框架已趋于平稳、标准化，向 Web Components 看齐；强运营背景下，移动端以前端开发为主，已成定局；5G 时代快来了，互联网的长期在线情况有可能会被打破。

#### 7、[利用"交叉观察者"这个小宝贝儿，轻松实现懒加载、吸顶、触底](https://juejin.im/post/5d665133e51d4561c83e7c83)

判断可视性的方法，基本就是监听 scroll 事件，或者是计时器循环判断来做这个判断，但是由于其高频的计算频率，会导致浏览器性能的损失，尤其是，如果一个同一个页面中，有多个地方，需要这样的判断，那么就需要绑定多个scroll事件，或者有多个计时器在轮询的话，那么对性能的损失就更为客观了;IntersectionObserver 虽然当前受限于浏览器的支持性，该方法还不能用于生产环境中，但却不影响我们去先了解一下这个令人兴奋的API。

#### 8、[Vue 项目性能优化 — 实践指南](https://juejin.im/post/5d548b83f265da03ab42471d)

从代码、Webpack、基础 Web 技术多方面讲解Vue项目的性能优化思路。

#### 9、[Webpack优化——将你的构建效率提速翻倍](https://juejin.im/post/5d614dc96fb9a06ae3726b3e)

Webpack 已经逐渐成为了前端构建体系的一大霸主，但随着业务代码不断增加，项目深度不断延伸，我们的构建时长也会因此不断增加。本文通过一个案例，向你展示如何分析构建病根、优化构建体验。

#### 10、[探秘 Vue3.0 - Composition API 在真实业务中的尝鲜姿势](https://mp.weixin.qq.com/s/Q6A0wn39mYOSXm2--Q_IOA)

Vue3.0 将抛弃之前的 Class API 的提案，选择了 Function API。目前，vue 官方 也提供了 Vue3.0 特性的尝鲜版本，前段时间叫 `vue-function-api`，目前已经改名叫 `composition-api`。

## 经典文章

#### [React Native 异常处理](https://github.com/HuJiaoHJ/blog/issues/13)

详细阐述了RN的异常监控方法，原理。对于业务的稳定性以及异常监控有帮助。

#### [你的Tree-Shaking并没什么卵用](https://zhuanlan.zhihu.com/p/32831172)

本文将探讨tree-shaking在当下的现状，以及研究为什么tree-shaking依旧举步维艰的原因，最终总结当下能提高tree-shaking效果的一些手段。

#### [你不知道的前端算法之热力图的实现](https://zhuanlan.zhihu.com/p/32362059)

通过canvas用非常巧妙的方法实现热力图的颜色渐变效果。

#### [深入 CommonJs 与 ES6 Module](https://segmentfault.com/a/1190000017878394)

文章介绍了 Commonjs 和 ES6 Module，导入导出的语法规则，路径解析规则，两者的区别，容易混淆的地方，在不同环境的区别，在不同环境的使用，Tree-shaking，与 webpack，rollup 的区别。

## 资源

#### [How Web Content Can Affect Power Usage](https://webkit.org/blog/8970/how-web-content-can-affect-power-usage/)

如今，用户将大量浏览网页的时间花在移动设备上，而移动设备的能耗是一个不容忽视的问题。WebKit 团队的这篇文章讨论了如何找到页面中能耗过大的问题，并给出了一些具体的让网页更节能的方法和建议。

The Baseline Interpreter: a faster JS interpreter in Firefox 70
FireFox 70 给 JavaScript 执行管道添加了新的一层：Baseline Interpreter，该解释器使得页面加载速度提升了 2-8% 左右，他们在博文中介绍了是如何做到这一点的。

## 废弃

#### [别再说虚拟 DOM 快了，要被打脸的](https://mp.weixin.qq.com/s/XR3-3MNCYY2pg6yVwVQohQ)

虚拟DOM越来越流行，React、vue2都使用了虚拟DOM。不少人会有种错误的认识，那就是虚拟DOM很快，比原生DOM还快。其实不管是React还是vue，虚拟DOM最终还是要调用原生DOM api去创建或者更新节点，所以虚拟DOM一定是会比原生DOM慢。而像React、vue这些框架却给我们带来到好处如下：

（1）提供了一个更为方便到API来创建UI，让我们只关注业务代码，而不必操心底层DOM到操作。

（2）不论数据如何变化，框架都会以最小的代价来进行DOM更新。

理由：内容老、深度不够。

#### [腾讯在线教育小程序开发实践之路](https://juejin.im/post/5d15fc3be51d4510b71da637)

北京GMTC大前端技术会议小程序专场，分享了该话题。

理由：内容虽然很全，但是亮点不够。


#### [Optimizing SVGs in data URIs](https://codepen.io/tigt/post/optimizing-svgs-in-data-uris)

介绍如何优化data URI中的svg代码。与base64相比，简化后的svg代码体积更小。

理由：文章比较老。

#### [Google 的 Pagespeed 的工作原理：提升你的页面分数和搜索引擎排名](https://mp.weixin.qq.com/s/DYsb3yn6QcbkZNJMUb8WNA)

通过这篇文章，我们将揭开PageSpeed 最为重要的页面速度评分的计算方法。

理由：适合科普，但深度不够。

#### [从零一步一步实现一个完整版的Promise](https://juejin.im/post/5d59757f6fb9a06ae76405c6)

虽然优先选择使用async/await，但是目前我们代码里面还是经常使用promise，所以简单了解下promise的实现也是非常必要的。

理由：同质化严重。

#### [前后端同构-如何解决Cookie问题](http://wqadmin.jd.com/webstatic/blogs/2019/09/04/node-zone-analysis/)

原创文章，请在内网打开。如何在Node中创建一个java ThreadLocal的特性。

理由：还在完善ing。


#### [可选链式访问](https://v8.dev/features/optional-chaining)

解决a && a.b && a.b.c && a.b.c.length 安全访问的ES特性。

#### [【重构系列】什么时候需要进行代码重构？](https://juejin.im/post/5d6695f051882554e26201d2)

重构是一个被说烂了的名词，可能还是一个让人听完心有余悸的名词。大多数开发对重构的理解，就是推翻以前的软件，重新花时间设计架构一个和界面一模一样的东西。但是不是这样呢？到底什么才是真正的重构呢？看完这篇文章，再来思考你是不是该重构了。

理由：纯文字太多，期待下篇。

#### [深拷贝的终极探索](https://yanhaijing.com/javascript/2018/10/10/clone-deep/)

关于深拷贝我们没有考虑过的问题。

理由：不够深入。

#### [为什么HTTPS比HTTP更安全?](https://mp.weixin.qq.com/s/liH6t4rYq0MXvG4-xUIfOw)

近几年，互联网发生着翻天覆地的变化，尤其是我们一直习以为常的HTTP协议，在逐渐的被HTTPS协议所取代，在浏览器、搜索引擎、CA机构、大型互联网企业的共同促进下，互联网迎来了“HTTPS加密时代”，HTTPS将在未来的几年内全面取代HTTP成为传输协议的主流。

理由：大家都知道的。



