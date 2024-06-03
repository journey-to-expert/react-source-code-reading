# 閱讀 React 原始碼讀書會

## Planning

### 主題：如何用 debugger, useState 的底層運作原理

#### 討論內容

Video：
- [React Internals Deep Dive 1 - Hello World! Debugging](https://www.youtube.com/watch?v=OcB3rTln-fI&list=PLvx8w9g4qv_p-OS-XdbB3Ux_6DMXhAJC3&index=1)
- [React Internals Deep Dive 5 - How does useState work internally?](https://www.youtube.com/watch?v=svaUEHMuv9w&list=PLvx8w9g4qv_p-OS-XdbB3Ux_6DMXhAJC3&index=5)

#### 日期：待定  
#### 主持人：待定  

---

### 主題：react fiber and reconciliation

#### 討論內容

Video：
- [What Is React Fiber? React.js Deep Dive #2](https://www.youtube.com/watch?v=0ympFIwQFJw&list=PLxRVWC-K96b0ktvhd16l3xA6gncuGP7gJ&index=2)
- [React Internals Deep Dive 15 - How does React traverse Fiber Tree internally?](https://www.youtube.com/watch?v=3nwupG2Joaw&list=PLvx8w9g4qv_p-OS-XdbB3Ux_6DMXhAJC3&index=15)
- [Understanding React's UI Rendering Process](https://www.youtube.com/watch?v=i793Qm6kv3U)

Article：
- https://github.com/acdlite/react-fiber-architecture
- https://tusharf5.com/posts/react-fiber-overview/
- https://makersden.io/blog/look-inside-fiber

#### 日期：待定  
#### 主持人：待定  

---

### 主題： signals

#### 討論內容：

react 是用 react fiber, reconciliation 和 virtual dom 來對真實的 dom 進行更新和 render，那其他框架（例如：vue, angular, ember, solid, svelte, qwik...）是用什麼方法來實現這件事情？這次的主題主要會聚焦在 signals 這個設計上面。

Video：
- [Rich Harris - Rethinking reactivity](https://www.youtube.com/watch?v=AdNJ3fydeao)

Article
- A Hands-on Introduction to Fine-Grained Reactivity：https://dev.to/ryansolid/a-hands-on-introduction-to-fine-grained-reactivity-3ndf
- JavaScript Signals standard proposal：https://github.com/tc39/proposal-signals
- Signals vs. Observables, what's all the fuss about?：https://www.builder.io/blog/signals-vs-observables
- useSignal() is the Future of Web Frameworks：https://www.builder.io/blog/usesignal-is-the-future-of-web-frameworks
- Signal - 蓄勢待發的 Virtual DOM 殺手：https://maxlee.me/posts/signal

#### 日期：待定  
#### 主持人：待定  

## Records

## Other Reference

- Understanding React：https://dontimitateunderstand.com/p/understanding-react
- React Internals Deep Dive：https://youtube.com/playlist?list=PLvx8w9g4qv_p-OS-XdbB3Ux_6DMXhAJC3&si=7rXjDGeY5mSYUORf
