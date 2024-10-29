<p align="center">
<div style="width:150px;margin:auto;">
<div align="center">
  <img src="https://img1.baidu.com/it/u=1287072252,2237298563&fm=253&fmt=auto&app=120&f=JPEG">
</div>
</div>
</p>
<h1 align="center">SSY-UI-VITE</h1>
<p align="center">
  基于 Vite 栈的前端工程化实践
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/WinterBreeze052/ssy-ui-vite?color=red">
</p>

## Features

- 一基于 Vue 框架
- 支持JSX 与Vue单文件组件
- Jest + Vue3 plugins实现单元测试
- Eslint + Prettier + Husky 语法检查
- 采用Rollup构建
- Vitepress + Vercel 文档网站搭建
- 基于ActionCI实现持续集成与交付

## Install

```bash
import Vue from "vue"
import SSYUI from "ssy-ui"

const App = {
  template:`
  <SButton color="blue">主要按钮</SButton>
  `,
};

createApp(App)
  .use(SSYUI)
  .mount('#app');
```

## Quick Start

如果希望尽快上手，可以访问[🔨 SSY-UI-VITE 是什么? | VitePress](https://ssy-ui-vite-five.vercel.app/)
