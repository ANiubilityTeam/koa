---
theme: geek-black
---
# koa+mysql

## 1. 简介
`Koa` 作为 `Express` 原班人马打造的新生代 Node.js Web 框架，自从发布以来就备受瞩目。凭借精巧的 “洋葱模型” 和对 `Promise` 以及 `async/await` 异步编程的完全支持，`Koa` 框架自从诞生以来就吸引了无数 Node 爱好者。然而 `Koa` 本身只是一个简单的中间件框架，要想实现一个足够复杂的 Web 应用还需要很多周边生态支持。

## 2. 准备
### 2.1 环境准备
- Node.js：10.x 及以上
- npm：6.x 及以上
- Koa：2.x
- MySQL：推荐稳定的 5.7 版本及以上
- TypeORM：0.2.x
### 学习目标
- 如何编写 `Koa` 中间件
- 通过 `@koa/router` 实现路由配置
- 通过 `TypeORM` 连接和读写 `MySQL` 数据库（其他数据库都类似）
- 了解 `JWT` 鉴权的原理，并动手实现
- 掌握 `Koa` 的错误处理机制
### 初始代码
git clone -b init-porject https://github.com/ANiubilityTeam/koa.git


