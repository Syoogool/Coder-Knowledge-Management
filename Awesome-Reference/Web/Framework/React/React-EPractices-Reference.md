[![章节头](https://parg.co/UGo)](https://parg.co/b4z) 
 - [React 工程实践资料索引](#react-%E5%B7%A5%E7%A8%8B%E5%AE%9E%E8%B7%B5%E8%B5%84%E6%96%99%E7%B4%A2%E5%BC%95)
- [StyleGuide: 样式指南](#styleguide-%E6%A0%B7%E5%BC%8F%E6%8C%87%E5%8D%97)
  * [CodeStyle: 代码风格](#codestyle-%E4%BB%A3%E7%A0%81%E9%A3%8E%E6%A0%BC)
  * [Functional React: 函数式 React](#functional-react-%E5%87%BD%E6%95%B0%E5%BC%8F-react)
  * [HOCs: 高阶组件](#hocs-%E9%AB%98%E9%98%B6%E7%BB%84%E4%BB%B6)
- [Performance: 性能优化](#performance-%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96)
  * [Tool: 工具](#tool-%E5%B7%A5%E5%85%B7)
  * [Code Splitting & Components Decomposition: 代码分割与组件解耦](#code-splitting--components-decomposition-%E4%BB%A3%E7%A0%81%E5%88%86%E5%89%B2%E4%B8%8E%E7%BB%84%E4%BB%B6%E8%A7%A3%E8%80%A6)
- [Production: 生产环境](#production-%E7%94%9F%E4%BA%A7%E7%8E%AF%E5%A2%83)
  * [Test: 测试](#test-%E6%B5%8B%E8%AF%95)
  * [StaticType: 静态类型检测](#statictype-%E9%9D%99%E6%80%81%E7%B1%BB%E5%9E%8B%E6%A3%80%E6%B5%8B)
  * [Server Side Rendering: 服务端渲染](#server-side-rendering-%E6%9C%8D%E5%8A%A1%E7%AB%AF%E6%B8%B2%E6%9F%93)
  * [Preact](#preact)
- [Architecture: 应用架构](#architecture-%E5%BA%94%E7%94%A8%E6%9E%B6%E6%9E%84)
- [Reconciliation: 调和与 React 内部原理](#reconciliation-%E8%B0%83%E5%92%8C%E4%B8%8E-react-%E5%86%85%E9%83%A8%E5%8E%9F%E7%90%86)
  * [Virtual DOM](#virtual-dom)
  * [Stack Reconciler](#stack-reconciler)
  * [Fiber](#fiber) 


# React 工程实践资料索引
# StyleGuide: 样式指南

- [2017-Characteristics of an Ideal React Architecture](https://parg.co/bD4): 
- [2016-来自 AlloyTeam 的 React.js 2016最佳实践](http://www.alloyteam.com/2016/01/reactjs-best-practices-for-2016/)
- [2016-React Patterns](http://reactpatterns.com/):  Patterns for React Developers

- [2017-10 React mini-patterns](https://hackernoon.com/10-react-mini-patterns-c1da92f068c5#.5v2hpgurn): Over the last few years, I’ve worked on a handful of decent-sized React projects, and many, many pint-sized ones. Throughout this magical journey, a number of patterns have come up that I find myself repeating again and again.
- [Understanding Component-Based Architecture](https://medium.com/@dan.shapiro1210/understanding-component-based-architecture-3ff48ec0c238#.smfo6yyhj)

- [Share Code between React and React Apps using Higher Order Components](https://hackernoon.com/code-reuse-using-higher-order-hoc-and-stateless-functional-components-in-react-and-react-native-6eeb503c665#.4z4q9o6k2)

- [Higher Order React Components](http://natpryce.com/articles/000814.html)

- [Renderless Components or How Logic Doesn't Always Need a UI](http://kyleshevlin.com/renderless-components/)

- [Higher-Order Components in React](http://6me.us/MUHBdp)

- [jsinspect](https://github.com/danielstjules/jsinspect)

- [Our Best Practices for Writing React Components](https://medium.com/code-life/our-best-practices-for-writing-react-components-dec3eb5c3fc8#.mh12fzmoi)
- [2017-Avoiding deeply nested component trees](https://parg.co/beQ): By passing child components down instead of data you can avoid passing data down through many levels of components.

- [2017-Avoiding deeply nested component trees](https://parg.co/beQ): By passing child components down instead of data you can avoid passing data down through many levels of components.

- [2017-8 Key React Component Decisions](https://parg.co/Um6): Standardize your React development with these key decisions.
## CodeStyle: 代码风格
- [eslint-plugin-react【Project】](https://parg.co/b11): React specific linting rules for ESLint.
## Functional React: 函数式 React

- [2017-Functional setState is the future of React](https://parg.co/bMW): Declare state changes separately from the component classes.
- [non-functional-react-js](https://medium.com/@arqex/non-functional-react-js-6e020ce27ee2#.cj3dcxl4j)
- [recompose【Project】](https://github.com/acdlite/recompose/blob/master/docs/API.md#withstate): A React utility belt for function components and higher-order components.
- [2016-Why The Hipsters Recompose Everything](https://medium.com/javascript-inside/why-the-hipsters-recompose-everything-23ac08748198): Building a Utility Library for React
- [2017-Top 5 Recompose HOCs](https://parg.co/bJV): Today we’ll be going through my 5 (in no particular order) favorite Recompose Higher Order Components.
- [2017-Higher Order Components with Functional Patterns Using Recompose](https://egghead.io/courses/higher-order-components-with-functional-patterns-using-recompose): In this course, you will learn to use many of the most powerful and convenient higher-order components within Recompose by coding several real-world examples. Using recompose looks very different from “vanilla” React; so you will also get comfortable with the look and feel of a “recomposed” component. The best part is no more need for class components! You’ll learn how to use Recompose to both modify components and also create your own higher-order components.
- [Functional React Series — Part 1: Get your App outta my Component](https://medium.com/@adamterlson/functional-react-series-part-1-get-your-app-outta-my-component-92656ae13e25#.q47pt8fga)

## HOCs: 高阶组件

- [Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.uz8irdipq)
- [2017-Why you should keep your react components pure by using HOCs](https://hackernoon.com/why-you-should-keep-your-react-components-pure-by-using-hocs-67e5c7f80c81): In this article I show how decomposing state from the presentational layer can both reduce complexity and promote code re-use with some React examples— a win-win situation helping to tame the challenges of developing SPAs. Although I’m using React, the lessons are universal and can apply to any framework.

- [redux-without-profanity-components](https://tonyhb.gitbooks.io/redux-without-profanity/content/components.html)
- [Mixins Are Dead. Long Live Composition](https://medium.com/@dan_abramov/mixins-are-dead-long-live-higher-order-components-94a0d2f9e750#.ldkxkz8na)
- [react-higher-order-components-in-depth](https://medium.com/@franleplant/react-higher-order-components-in-depth-cf9032ee6c3e#.wn52tt10t)
- [container-components](https://medium.com/@learnreact/container-components-c0e67432e005#.h775w7ifn)

- [2017-Understanding Higher Order Components](https://parg.co/biZ): Making sense of the rapidly changing React best practice.
- [React Higher Order Components in depth](https://medium.com/@franleplant/react-higher-order-components-in-depth-cf9032ee6c3e#.52i6nt3at)

- [2016-Building HOCs with Recompose](https://medium.com/front-end-developers/building-hocs-with-recompose-7debb951d101)

# Performance: 性能优化
- [React Office Site —— Optimizing Performance](https://facebook.github.io/react/docs/optimizing-performance.html): For many applications, using React will lead to a fast user interface without doing much work to specifically optimize for performance. Nevertheless, there are several ways you can speed up your React application.

- [2017-Keep Your React Redux Healthy, Performance Optimization Story](https://parg.co/bCn): I am here to be honest about React optimization.
- [2017-React at Light Speed](https://blog.vixlet.com/react-at-light-speed-78cd172a6411): Lessons in optimizing performance at Vixlet
- [2017-45% Faster React Functional Components, Now](https://parg.co/bMa)
- [2017-Our Best Practices for Writing React Components](https://engineering.musefind.com/our-best-practices-for-writing-react-components-dec3eb5c3fc8#.3kin14vrf): When I first started writing React, I remember seeing many different approaches to writing components, varying greatly from tutorial to tutorial. Though the framework has matured considerably since then, there doesn’t seem to yet be a firm ‘right’ way of doing things.
- [2017-Memoize React components](https://github.com/planttheidea/moize)
- [2017-React at Light Speed](http://6me.us/dx5)
- [Should I use shouldComponentUpdate?](http://jamesknelson.com/should-i-use-shouldcomponentupdate/)
- [React移动web极致优化](https://github.com/lcxfs1991/blog/issues/8?f=tt&hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
- [ProReact中关于性能的章节]()
- [component-rendering-performance-in-react](https://medium.com/modus-create-front-end-development/component-rendering-performance-in-react-df859b474adc#.rjjvtwgs8)
- [React应用优化：避免不必要的render](http://www.broadview.com.cn/article/77?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
- [React Rally: Animated — React Performance Toolbox](http://blog.vjeux.com/2015/javascript/react-rally-animated-react-performance-toolbox.html)
- [How to Benchmark React Components: The Quick and Dirty Guide](https://medium.com/code-life/how-to-benchmark-react-components-the-quick-and-dirty-guide-f595baf1014c#.w1t22c86k)
- [React.js pure render performance anti-pattern](https://medium.com/@esamatti/react-js-pure-render-performance-anti-pattern-fb88c101332f#.b9vwbt1jy)
- [A DEEP DIVE INTO REACT PERF DEBUGGING](http://benchling.engineering/deep-dive-react-perf-debugging/)
- [React at 60fps](https://medium.com/@okonetchnikov/react-at-60fps-4e36b8189a4c#.enqkaabwg)
- [React Performance Optimization](https://medium.com/@nesbtesh/react-performance-optimization-28ec5b61fff3#.lx9g6ewdg)
- [React Performance Optimization](http://6me.us/t73W9): Performance optimization can be a big pain with any language. Especially when you are optimizing your app and you have no idea what to optimize. React has some really nice tools to do this, I will be talking about one specifically that will make your life a lot better.-  [2017-React at Light Speed, Lessons in optimizing performance at Vixlet](https://blog.vixlet.com/react-at-light-speed-78cd172a6411): Here we will share some of the lessons we have learned along the way.
- [2017-Optimizing React Rendering](https://flexport.engineering/optimizing-react-rendering-part-1-9634469dca02) 
- [2017-React, Inline Functions, and Performance](https://cdb.reacttraining.com/react-inline-functions-and-performance-bdff784f5578)
## Tool: 工具
- [High Performance React: 3 New Tools to Speed Up Your Apps](https://parg.co/b1v): In this post I’ll highlight tools and techniques for making React apps fast. Each section also has an interactive, and (hopefully) fun demo!
- [why-did-you-update【Project】](https://github.com/garbles/why-did-you-update): Puts your console on blast when React is making unnecessary updates.




## Code Splitting & Components Decomposition: 代码分割与组件解耦

- [2017-React Loadable【Project】](https://github.com/thejameskyle/react-loadable):  [2017-Introducing React Loadable](http://6me.us/mNHi)、[react-loadable-visibility【Project】](https://github.com/stratiformltd/react-loadable-visibility)
- [2017-Code Splitting in Create React App](http://serverless-stack.com/chapters/code-splitting-in-create-react-app.html): This chapter is an extra step that can help speed up the initial load time of your React app.
- [2017-https://parg.co/bXz](https://parg.co/bXz): Techniques for decomposing React components. React components have a lot of power and flexibility. With so many tools at your disposal, it is incredibly easy for components to grow over time, become bloated and do too much.
- [2017-Writing Clean and Concise React Components by Making Full Use of ES6/7 Features and the Container-Component Pattern](https://parg.co/b1B)
 



# Production: 生产环境
## Test: 测试
- [2017-Testing React Applications【Series】](https://blog.logrocket.com/testing-react-applications-part-1-of-3-ebd8397917f3)：With React and the ecosystem of testing tools that have emerged around it, it’s finally possible to build robust, scalable tests that provide strong guarantees on code correctness.
- [Snapshot Testing React Components with Jest](https://semaphoreci.com/community/tutorials/snapshot-testing-react-components-with-jest)

## StaticType: 静态类型检测
- [2017-Typing Higher-order Components in Recompose With Flow](https://parg.co/bDu) 

## Server Side Rendering: 服务端渲染
- [2017-Introducing Rapscallion【Project】](http://formidable.com/blog/2017/introducing-rapscallion/): a new approach for server-side rendering React applications.

- [2017-Server-Side React Rendering](https://css-tricks.com/server-side-react-rendering/): In this tutorial, we'll take you through a server side rendering example step-by-step. including working around a common roadblock for React apps that talk to APIs. 
- [React 同构技术](https://zhuanlan.zhihu.com/p/21492780)
- [React on the Server for Beginners: Build a Universal React and Node App](https://scotch.io/tutorials/react-on-the-server-for-beginners-build-a-universal-react-and-node-app?ref=mybridge.co)
- [Redux官方文档 ServerSideRendering](http://redux.js.org/docs/recipes/ServerRendering.html)
- [玩转React服务端渲染](https://blog.coding.net/blog/React-server-rendering)
- [isomorphic-redux-app](https://github.com/caljrimmer/isomorphic-redux-app)
- [Client-side vs. server-side rendering: why it’s not all black and white.](https://medium.freecodecamp.com/what-exactly-is-client-side-rendering-and-hows-it-different-from-server-side-rendering-bd5c786b340d#.n4zils8st): Since the dawn of time, the conventional method for getting your HTML up onto a screen was by using server-side rendering. It was the only way. You loaded up your .html pages on your server, then your server went and turned them into useful documents on your users’ browsers.

- [Introducing Rapscallion](http://formidable.com/blog/2017/introducing-rapscallion/): a new approach for server-side rendering React applications.




## Preact
- [The Inner Workings Of Virtual DOM](https://medium.com/@rajaraodv/the-inner-workings-of-virtual-dom-666ee7ad47cf#.or5425hja)

- [Webpack2 boilerplate for building SPA / PWA / offline front-end apps with Preact](https://github.com/lukeed/preact-starter)
- [司徒正美 preact 源码学习系列文章](https://segmentfault.com/a/1190000010336457)
# Architecture: 应用架构

# Reconciliation: 调和与 React 内部原理
- [2017-React Internals](http://www.mattgreer.org/articles/react-internals-part-one-basic-rendering/): In this five part series, we will “recreate” React from the ground up, learning how it works along the way. Once we’ve finished, you should have a good grasp of how React works, and when and why it calls the various lifecycle methods of a component.
## Virtual DOM 

- [2017-react diff 原理](https://cloud.tencent.com/community/article/654179001489391651?fromSource=gwzcw.114428.114428.114428)：React diff 作为 Virtual DOM 的加速器，其算法上的改进优化是 React 整个界面渲染的基础，以及性能提高的保障，同时也是 React 源码中最神秘、最不可思议的部分，本文将剖析 React diff 的不可思议之处。
- [Performance Calendar:React’s diff algorithm](http://calendar.perfplanet.com/2013/diff/)
- [React 源码剖析系列 － 不可思议的 react diff](https://zhuanlan.zhihu.com/p/20346379?refer=purerender)
- [React 源码剖析系列 － 解密 setState](https://zhuanlan.zhihu.com/p/20328570?refer=purerender)
- [深入浅出React（四）：虚拟DOM Diff算法解析](http://www.infoq.com/cn/articles/react-dom-diff)
- [ReactJS | Learning Virtual DOM and React Diff Algorithm](http://www.oyecode.com/2015/09/reactjs-learning-virtual-dom-and-react.html)
- [react-fiber-architecture](https://github.com/acdlite/react-fiber-architecture)




## Stack Reconciler

- [Dive into setState() method in React](https://gist.github.com/ajhsu/e259392f06aa8e3bf5c9)
- [Dive into React codebase: Handling state changes](http://reactkungfu.com/2016/03/dive-into-react-codebase-handling-state-changes/)
- [2017-react-reconciler-demo【Project】](https://github.com/lukebelliveau/react-reconciler-demo): A simple implementation of React's stack reconciler. This is much different from the real implementation, but demonstrates the concepts.
- [ON THE ASYNC NATURE OF `SETSTATE` IN REACT](http://thereignn.ghost.io/on-the-async-nature-of-setstate-in-react/)
- [2017-Under-the-hood-ReactJS](https://github.com/Bogdan-Lyashenko/Under-the-hood-ReactJS): Entire ReactJS code base explanation by visual block schemes (Stack+Fiber versions)

## Fiber

- [2017-React Fiber resources](https://github.com/koba04/react-fiber-resources): This is for resources for React Fiber.
- [2017-A look inside React Fiber - how work will get done.](http://makersden.io/blog/look-inside-fiber/): This post will go outside-in - starting from calling the render function in client JS and changing state of a component, down to describing the steps taken by Fiber to do all the work.

- [2017-React Fiber Architecture](https://github.com/acdlite/react-fiber-architecture): A description of React's new core algorithm, React Fiber.
- [2017-React 的新引擎— React Fiber 是什么？](https://parg.co/bgb)：稍有经验的前端工程师会知道，页面的 DOM 改变，就会导致页面重新计算 DOM，进行重绘或者重排，DOM 结构复杂或者频繁操作 DOM 通常是性能瓶颈产生的原因。而网站从最开始比较简单，开始变的越来越复杂，用户交互也会越来越多，怎么去减轻 DOM 操作带来的性能损耗就变得重要起来。
- [2017-React Fiber 是什么](https://zhuanlan.zhihu.com/p/26027085)：React Fiber 这个大改变 Facebook 已经折腾两年多了，刚刚结束不久的 React Conf 2017 会议上，Facebook 终于确认，React Fiber 会搭上 React 下一个大版本v16的顺风车发布。
- [2017-React 新引擎 React Fiber 究竟要解决什么问题？](https://parg.co/btw)：Facebook 正在以流行的 JavaScript 框架 React 为基础开发一个全新的架构。这个名为 React Fiber 的全新设计改变了检测变更的方法和时机，借此可改进浏览器端和其他渲染设备的响应速度。 这一 全新架构 最初已于 2016 年 7 月公开发布，其中蕴含着过去多年来 Facebook 不断改进的工作成果。该架构可向后兼容，彻底重写了 React 的协调（Reconciliation）算法。该过程可用于确定出现变更的具体时间，并将变更传递给渲染器。
- [2017-React Conf: A Cartoon Intro to Fiber](https://www.youtube.com/watch?v=ZCuYPiUIONs)


