<h1 align="center">
    2021 前端开发手册
</h1>

## 简介

这是一份 2021 年前端开发手册，列举前端开发相关技术，提供相关技术的学习资源。下面的项目不用全部学习，可以选其中一些学习。

## 目录

1. **[HTML](#1-HTML)**
2. **[CSS](#2-CSS)**
3. **[JavaScript](#3-JavaScript)**
4. **[前端框架](#4-前端框架)**
5. **[前端工程化](#5-前端工程化)**
6. **[服务端渲染 SSR](#6-服务端渲染-SSR)**
7. **[静态站点生成器 SSG](#7-静态站点生成器-SSG)**
8. **[TypeScript](#8-TypeScript)**
9.  **[用 JS 去做服务器端](#9-用-JS-去做服务器端)**
10. **[桌面应用程序 Electron](#10-桌面应用程序-Electron)**
11. **[移动端混合开发](#11-移动端开发)**
12. **[前端架构 JAMStack](#12-前端架构-JAMStack)**
13. **[WebAssembly](#13-WebAssembly)**

---

## 1. HTML
  - DOCTYPE
  - HTML, XHTML, XML 差异性
  - HTML5 新特性 及 语义化标签
  - meta, img, script 等标签及其标签属性
  - 有兴趣可以了解 W3C 和 WHATWG HTML5 差异

### 文章

- :book: [HTML（超文本标记语言） —— MDN](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
- :book: [HTML5 —— W3C](https://www.w3.org/html/ig/zh/wiki/HTML5)
- :book: [HTML5 教程 —— w3school](https://www.w3school.com.cn/html/html_doctype.asp)
- :book: [HTML5 标准 —— WHATWG](https://whatwg-cn.github.io/html/#toc-dom)

### 视频

- :tv: [初识HTML(5)+CSS(3)-2020升级版 —— 慕课网](https://www.imooc.com/learn/9)
- :tv: [Web前端开发 —— 北京工业大学MOOC](https://www.icourse163.org/course/BFU-1003382003)

**[:arrow_up: 返回目录](#目录)**

---

## 2. CSS
- CSS 基础
- CSS 布局
- CSS 动画
- CSS 预处理器（sass, less, stylus）

### 文章

- :book: [CSS（层叠样式表）](https://developer.mozilla.org/zh-CN/docs/Web/CSS)
- :book: [CSS现状和如何学习 —— 大漠](https://www.w3cplus.com/css/learning-css.html)

### 视频

- :tv: [初识HTML(5)+CSS(3)-2020升级版 —— 慕课网](https://www.imooc.com/learn/9)

**[:arrow_up: 返回目录](#目录)**

---

## 3. JavaScript

- JavaScript 基础
- ES6
- 面向对象编程 和 函数式编程

<!-- TODO: -->
### 文章

- :book: [CSS（层叠样式表）](https://developer.mozilla.org/zh-CN/docs/Web/CSS)
- :book: [CSS现状和如何学习 —— 大漠](https://www.w3cplus.com/css/learning-css.html)

### 视频
<!-- TODO: -->
- :tv: [初识HTML(5)+CSS(3)-2020升级版 —— 慕课网](https://www.imooc.com/learn/9)

**[:arrow_up: 返回目录](#目录)**

---

## 4. 前端框架

- Vue
  - 路由（Vue-Router）
  - 状态管理（Vuex）
- React
  - JSX
  - Class Component, Hooks
  - 路由（React-Router, React-Router-Dom）
  - 状态管理（Redux, Mobx, Context API）
- Angular
  - 状态管理（Service, NgRx, RxJS）
- Svelte
  - 路由（svelte-spa-router）
  - 状态管理（Context API）

### 文章
- :book: [vue.js官网](https://cn.vuejs.org/)
- :book: [介绍 | Vue Router](https://router.vuejs.org/zh/)
- :book: [Vuex 是什么? | Vuex](https://vuex.vuejs.org/zh/)
- :book: [React 官方中文文档 – 用于构建用户界面的 JavaScript 库](https://react.docschina.org/)
- :book: [React Router 中文文档](http://react-guide.github.io/react-router-cn/index.html)
- :book: [Redux 中文文档](https://www.redux.org.cn/)
- :book: [MobX 中文文档](https://cn.mobx.js.org/)
- :book: [Angular 中文网](https://angular.cn/docs)
- :book: [NgRx Docs](https://ngrx.io/docs)
- :book: [RxJS 中文文档](https://cn.rx.js.org/)
- :book: [Svelte中文文档](https://www.sveltejs.cn/)

### 视频
- :tv: []()
<!-- TODO: -->

**[:arrow_up: 返回目录](#目录)**

---

## 5. 前端工程化

- 包管理工具（npm, yarn）
- JavaScript 编译器（babel）
- 代码检测工具（ESlint）
- 自动化打包工具（webpack, rollup, parcel, gulp）

### 文章
- :book: [npm 中文文档 | npm 中文网](https://www.npmjs.cn/)
- :book: [Yarn 中文文档](https://yarn.bootcss.com/)
- :book: [Babel - 下一代 JavaScript 语法的编译器](https://www.babeljs.cn/)
- :book: [ESLint - 插件化的 JavaScript 代码检测工具](https://eslint.bootcss.com/)
- :book: [webpack 中文文档 | webpack 中文网](https://www.webpackjs.com/concepts/)
- :book: [rollup.js 中文文档 | rollup.js 中文网](https://www.rollupjs.com/)
- :book: [gulp 中文文档 - gulp.js 中文文档 | gulp.js 中文网](https://www.gulpjs.com.cn/)
- :book: [Parcel 中文网](https://zh.parceljs.org/)

### 视频
<!-- TODO: -->
- :tv: []()

**[:arrow_up: 返回目录](#目录)**

---

## 6. 服务端渲染 SSR

- Nuxt（Vue）
- Next（React）
- Sapper（Svelte）

### 文章
- :book: [Nuxt.js - Vue.js 通用应用框架](https://www.nuxtjs.cn/)
- :book: [Next.js - React 应用开发框架 | Next.js 中文网](https://www.nextjs.cn/)
- :book: [sapper中文网](https://www.iqi360.com/p/sapper_cn)

### 视频
<!-- TODO: -->
- :tv: []()


**[:arrow_up: 返回目录](#目录)**

---

## 7. 静态站点生成器 SSG

- Gridsome（Vue）
- Gatsby（React）

### 文章
- :book: [Gridsome 是一个免费、开源、基于 Vue.js 构建的框架](https://www.gridsome.cn/)
- :book: [GatsbyJS 中文网](https://www.gatsbyjs.cn/)

### 视频
<!-- TODO: -->
- :tv: []()

**[:arrow_up: 返回目录](#目录)**

---

## 8. TypeScript
- 和 JavaScript 的差异
- 基础类型
- OOP（模块，类，接口，继承，泛型等）

### 文章
- :book: [TypeScript中文网 · TypeScript——JavaScript的超集](https://www.tslang.cn/)
- :book: [TypeScript 入门教程 —— xcatliu](https://ts.xcatliu.com/)

### 视频

- :tv: [TypeScript从入门到精通视频教程-2020年新版](https://www.bilibili.com/video/BV1qV41167VD)

**[:arrow_up: 返回目录](#目录)**

---


## 9. 用 JS 去做服务器端

- Node.js
  - 单线程、事件驱动、非阻塞I/O
  - 框架（Express, Koa，Nest）

- Deno

### 文章
- :book: [node.js官网](https://nodejs.org/zh-cn/)
- :book: [Express - 基于 Node.js 平台的 web 应用开发框架](https://www.expressjs.com.cn/)
- :book: [Koa (koajs) -- 基于 Node.js 平台的下一代 web 开发框架](https://www.koajs.com.cn/)
- :book: [Nestjs中文网](https://www.itying.com/nestjs/)
- :book: [Deno 中文手册](https://manual.deno.js.cn/)

**[:arrow_up: 返回目录](#目录)**

---

## 10. 桌面应用程序 Electron

Electron.js是可以通过HTML，CSS，JavaScript开发跨平台的桌面应用程序。
- 基础语法，API
- 编译
- 性能优化
- 调试
- 部署


### 文章
- :book: [Electron 文档](https://www.electronjs.org/docs/tutorial/quick-start)

### 视频
- :tv: [Electron免费视频教程 —— bilibili](https://www.bilibili.com/video/BV177411s7Lt)

**[:arrow_up: 返回目录](#目录)**

---

## 11. 移动端开发

- React Native
- Flutter
- Ionic

### 文章
- :book: [React Native 中文网 · 使用React来编写原生应用的框架](https://reactnative.cn/)
- :book: [Flutter中文网](https://flutterchina.club/)
- :book: [Ionic Framework - Ionic Documentation](https://ionicframework.com/docs)

### 视频
- :tv: [2020前端React-Native跨平台APP实战](https://www.bilibili.com/video/BV1nE411N7js)
- :tv: [Flutter基础视频教程 —— bilibili](https://www.bilibili.com/video/BV1nE411N7js)
- :tv: [Dart Flutter入门实战视频教程 —— bilibili](https://www.bilibili.com/video/BV1S4411E7LY)

**[:arrow_up: 返回目录](#目录)**

---

## 12. 前端架构 JAMStack

JAMStack（JAM 代表 JavaScript，API 和 Markup）

是一种使用 Static Site Generators (SSG) 技术、不依赖 Web Server 的前端架构。

### 文章
- :book: [jamstack 官网](https://jamstack.org/)
- :book: [前端架构之 JAMStack](https://zhuanlan.zhihu.com/p/137809668)

### 视频
- :tv: [What is JAMStack](https://www.bilibili.com/video/BV1Vf4y1B752?from=search&seid=10493721279094767258)

**[:arrow_up: 返回目录](#目录)**

---

## 13. WebAssembly

WebAssembly 是一种新的编码方式，可以在现代的网络浏览器中运行底层字节码。

### 文章
- :book: [WebAssembly —— MDN](https://developer.mozilla.org/zh-CN/docs/WebAssembly)
- :book: [WebAssembly 中文网|Wasm 中文文档](https://www.wasm.com.cn/)
- :book: [WebAssembly 现状与实战](https://developer.ibm.com/zh/articles/wa-lo-webassembly-status-and-reality/)

### 视频
- :tv: [下一代web技术，WebAssembly入门教程 —— bilibili](https://www.bilibili.com/video/BV13i4y1n74s?from=search&seid=12264771612687170994)
- :tv: [WebAssembly入门 —— bilibili](https://www.bilibili.com/video/av81216794)

**[:arrow_up: 返回目录](#目录)**

---
<!-- 
## 14. 

### 文章
- :book: []()

### 视频
- :tv: []()

**[:arrow_up: 返回目录](#目录)**

--- -->
