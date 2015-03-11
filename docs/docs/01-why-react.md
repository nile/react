---
id: why-react
title: 为什么要React?
permalink: why-react.html
next: displaying-data.html
---
React is a JavaScript library for creating user interfaces by Facebook and Instagram. Many people choose to think of React as the **V** in **[MVC](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)**.
React是一个用来构建用户界面的javascript库，它Facebook和Instagram开发提供的，它聚焦在**[MVC](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)**中的V角色。

We built React to solve one problem: **building large applications with data that changes over time**. To do this, React uses two main ideas.

React只有一个目标，那就是数据驱动的大型应用。于是React始终保持两个核心。

### Simple 简单

Simply express how your app should look at any given point in time, and React will automatically manage all UI updates when your underlying data changes.

直接的展示你的app应该如何，React会在底层数据变化的时候自动管理界面变化和更新。

### Declarative 声明式

When the data changes, React conceptually hits the "refresh" button, and knows to only update the changed parts.

当数据变化时候，React启动刷新过程，并且控制只更新需要更新的部分。

## Build Composable Components 构建组合组件

React is all about building reusable components. In fact, with React the *only* thing you do is build components. Since they're so encapsulated, components make code reuse, testing, and separation of concerns easy.

React都是关于构建可重用的组件，事实上，在使用React的过程，你所要做的所有就是构建组件；因为组件都是封装的，所以更代码更容易重用，更容易测试，也更好的拆分关注点。

## Give It Five Minutes 5分钟启动

React challenges a lot of conventional wisdom, and at first glance some of the ideas may seem crazy. [Give it five minutes](http://37signals.com/svn/posts/3124-give-it-five-minutes) while reading this guide; those crazy ideas have worked for building thousands of components both inside and outside of Facebook and Instagram.



## Learn More

You can learn more about our motivations behind building React in [this blog post](http://facebook.github.io/react/blog/2013/06/05/why-react.html).
