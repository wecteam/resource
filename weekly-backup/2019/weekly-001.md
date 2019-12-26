
# WecTeam 前端周刊：第 001 期

## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 001 期发布时间：2019-08-30。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

### 1、[【原创】CSS Houdini实现动态波浪纹](https://mp.weixin.qq.com/s/YvX3zetS7Zt98cfWoK4UKQ)

本文作者@**黄浩群**。CSS Houdini 号称 CSS 领域最令人振奋的革新。CSS 本身长期欠 缺语法特性，可拓展性几乎为零，并且新特性的支持效率太低，兼容性差。而 Houdini 直接将 CSS 的 API 暴露给开发者，以往完全黑盒的浏览器解析流开始对外开放，开发者可以自定义属于自己的 CSS 属性，从而定制和扩展浏览器的展示行为。

### 2、[【原创】碰撞检测的向量实现](https://mp.weixin.qq.com/s/8Xn2d6__vc9_RfhhpwwMDA)

本文作者@**吴冠禧**。2D游戏中，通常使用矩形、圆形等来代替复杂图形的相交检测。因为这两种形状的碰撞检测速度是最快的。其中矩形包围盒又可以分为轴对齐包围盒（AABB, Axis Aligned Bounding Box）与转向包围盒（OBB, Oriented Bounding Box）。AABB与OBB的区别在于，AABB中的矩形的其中一条边和坐标轴平行，OBB的计算复杂度要高于AABB。根据不同的使用场景，可以用不同的方案。

### 3、[图解浏览器的基本工作原理](https://zhuanlan.zhihu.com/p/47407398)

可能每一个前端工程师都想要理解浏览器的工作原理。我们希望知道从在浏览器地址栏中输入 url 到页面展现的短短几秒内浏览器究竟做了什么；我们希望了解平时常常听说的各种代码优化方案是究竟为什么能起到优化的作用；我们希望更细化的了解浏览器的渲染流程。

### 4、[让你的网页更丝滑](https://juejin.im/post/5c860282e51d45531330e10e)

想让网页变得丝滑，首先，我们需要一个标准来判断什么样的网页是丝滑的；其次，我们要准确的测量出网页的性能数据；最后，使用有效的方法让网页变得丝滑。

### 5、[「2019 JSConf.Asia - 尤雨溪」在框架设计中寻求平衡](https://zhuanlan.zhihu.com/p/76622839)

项目前端框架选择是前期开发非常重要的一个工作，要权衡框架的优劣势，也要权衡开发的学习以及扩展维护成本。本文以目前流行的三大框架来阐述最佳平衡点，并对比了三大框架的优缺点，为框架选择做一个指导。

### 6、[领域驱动设计在前端中的应用](https://github.com/Vincedream/ddd-fe-demo)

本文结合问题分析了项目在开发与后期的维护中存在的问题，提出规范以及设计的重要性，为项目的开发以及后期的维护提供指导。

### 7、[马蜂窝容器化平台前端赋能实践](https://mp.weixin.qq.com/s/dJiZeu8jEhEj40OqEBIPog)

容器的使用，方便统一管理部署，尤其是对node应用的发布管理。

### 8、[可能是你见过最完善的微前端解决方案](https://mp.weixin.qq.com/s/qMd6k9xSSNjskN3wB5PGgA)

本文就一个具体的类型场景，着重介绍微前端架构可以带来的价值以及具体实践过程中需要关注的技术决策，并辅以具体代码，从而能真正意义上帮助你构建一个生产可用的微前端架构系统。

### 9、[这些Web API真的有用吗? 别问，问就是有用](https://juejin.im/post/5d5df391e51d453b1e478ad0)

没有不实用，只有不会用！科普几个不常见的Web API，简单实例教你如何轻松玩转！


## 经典文章

### [神一样的随机算法](https://mp.weixin.qq.com/s/vgWad2KTLubzaH5WrHtVew)

这篇文章，我们从一道经典面试题开始来探讨这个问题。这个面试题有很多形式，但其实背后的算法是一致的。

### [CSS 是如何影响浏览器元素在文档中的排列](https://mp.weixin.qq.com/s/qTd-JC4IIM0G5gpLmopg3w)

之前在项目的过程中遇到了一个问题，某个 div 希望始终显示在最上面，而在之后的元素都显示在它之下，当时设置了 z-index 也没有效果，不知道什么原因，因此找了一下 CSS 相关资料，解决了这个问题的同时，也学习了很多知识，特此和大家分享一下。

### [从Chrome源码看浏览器如何计算CSS](https://zhuanlan.zhihu.com/p/25380611)

从浏览器实现出发，讲述了CSS代码从解析道渲染的过程，中间穿插了许多书写CSS的要点，深入浅出，很有帮助。

### [Tree-Shaking性能优化实践 - 原理篇](https://juejin.im/post/5a4dc842518825698e7279a9)

本文所说的前端中的tree-shaking可以理解为通过工具"摇"我们的JS文件，将其中用不到的代码"摇"掉，是一个性能优化的范畴。

### [Tree-Shaking性能优化实践 - 实践篇](https://juejin.im/post/5a4dca1d518825128654fa78)

webpack2 发布，宣布支持tree-shaking，webpack 3发布，支持作用域提升，生成的bundle文件更小。 再没有升级webpack之前，增幻想我们的性能又要大幅提升了，对升级充满了期待。虽然工具自带的tree-shaking不能去除太多无用代码，在去除无用代码这一方面也还是有可以做的事情。我们从三个方面做里一些优化。

### [腾讯HTTPS性能优化实践](https://mp.weixin.qq.com/s/V62VYS8KFNKxJxfzMYefrw)

本文根据罗成在2016ArchSummit全球架构师（北京）峰会上的演讲整理而成。主要内容分以下三部分：计算性能的分析和优化；无密钥加载；证书优化。


## 资源

### [[实用工具]Flutter widget 在线预览](https://flutter-widget-livebook.blankapp.org/basics/introduction/)

在 Flutter 众多 Widget 中，并不是像前端 UI 组件那样直接预览效果；官方也只提供效果截图或者视频以及代码片段，想要体验效果，只能打开编辑器，复制代码片段，编译后通过模拟器查看；通过该工具可快速预览需要使用的 Widget 效果。

### [涨姿势！原来JavaScript运算符还可以这么玩](https://mp.weixin.qq.com/s/lTwvU7DcG515SQ6BcTs8eA)

## 废弃

### [浏览器的工作原理：新式网络浏览器幕后揭秘](https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)

### [大规模应用TypeScript「2019 JSConf -Brie Bunge」](https://juejin.im/post/5d5416226fb9a06b24431448)

本文阐述了typescript为项目的维护带来的优点以及如何将项目过渡到typescript。

### [JS 的5个不良编码习惯，现在就改掉吧](https://mp.weixin.qq.com/s/odouA6pFaeePm90-ocN_Kg)

良好的编码习惯，既能提升代码的健壮性，又方便代码风格的统一，增强团队凝聚力。

### [[视频]菲利普·罗伯茨：到底什么是Event Loop呢？](https://www.youtube.com/watch?v=8aGhZQkoFbQ)

也许是对 Event Loop 最好的诠释.找一个好的方式来解释 Javascript 实际运行情况并不那么容易；无论对 Event Loop 掌握多少，建议都看看，视频虽然有点老，但经典不会因时间褪色。

### [JavaScript中的位操作符](https://juejin.im/post/5d6281b15188252501776d27)

写了3年前端也没用到JS位运算？本文从原理出发结合实践讲解JS位运算，既有骚操作也有位运算在日常业务中的应用举例，并且在文章末尾结合leetCode几道典型的问题，文章比较完整和全面。

