# Build Your Own React

近几年 React 彻底改变了前端的开发方式，在 Web Component 未能成为现实之前首先确立了前端组件化的现实标准，我们在使用 React 的同时也可以不再关心一些细节问题。但是在 React 提供便利的同时，我们也应该明白它到底为我们做了什么，为什么这么做。

一些文章通过讲述 React 的使用或者最佳范式试图让你理解 React 干了什么，也有一些文章是直接分析 React 的源码。而只谈使用过于空泛，读源码的工作量又太大，容易陷入无边的细节。本文则试图填补这中间的空白，我们会实现一个简化版的 React -- React-tiny，覆盖 React 的一些核心功能。从而让我们身临其境地理解 React 到底为我们解决了什么问题，以及为什么要这么解决。

由于 React 本身过于复杂，笔者本身也不能非常全面的了解其具体的实现和表现，所以 React-tiny 并不会拘泥于 React 的真正实现方式，我会按照自己的理解尽可能贴近 React 的行为，如果有不一致的地方还望指正。

之前有尝试过通过多篇文章的方式来讲清楚，但是发现文章的篇幅很难一次性 cover 住这么多概念，介绍的内容一多表达就容易混乱，于是这次尝试通过电子书的形式，每个章节尝试讲清楚足够简单的概念和问题。

本电子书面向对 React 的一些基本概念（至少会用）有了解的开发者，需要了解一些 JavaScript 基础。

