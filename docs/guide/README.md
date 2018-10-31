---
sidebarDepth: 0
---

<p align="center" style="text-align: center">
  <a href="https://github.com/MPComponent/mpvue-weui">
    <img width="300" :src="$withBase('/assets/logo.png')" alt="mpvue-weui logo">
  </a>
  <p align="center" style="text-align: center">
   <a href="https://www.npmjs.com/package/mpvue-weui" target="_blank"><img src="https://img.shields.io/npm/v/mpvue-weui.svg?style=flat" alt="npm"></a>
   <a href="https://www.npmjs.com/package/mpvue-weui" target="_blank"><img src="https://img.shields.io/npm/dt/mpvue-weui.svg?style=flat" alt="npm"></a>
 </p>
</p>

<imgPreview imgUrl="/assets/mpvue-weui-qrcode.png"/>

## Mpvue-WeUI

`Mpvue-WeUI`是基于 `mpvue` 框架，同微信原生视觉体验一致的基础样式库，为微信小程序量身设计，令用户的使用感知更加统一。

## 相关说明
之前写了 [用 vue 写小程序，基于 mpvue 框架重写 weui](https://github.com/KuangPF/mpvue-weui),这个是在 mpvue 开源之初写的，开始的目的是想重写下 weui，然后写了一些踩坑文档。可能有点遗憾的是没有对其进行完整的封装，以至于在使用过程中就很不方便，在 issues 中也看到一些关于能不能封装成一个独立的 UI 框架的想法，加上大家也给了这个仓库这么多 ⭐️ ⭐️ ，因此决定将其封装成一个独立的 UI 框架：[mpvue-weui](https://github.com/MPComponent/mpvue-weui)。

## 开发预览

``` bash
1. git clone
git clone git@github.com:MPComponent/mpvue-weui.git

2. 安装依赖
npm install

3. 启动程序
npm run dev

4. 预览
打开微信开发者工具，新建项目，将目录指向 /dist 即可
```

## 贡献

欢迎各位大佬贡献代码，贡献方法如下：

* fork 本仓库到自己账户下
* 提交变更
* PR 到本仓库 （`dev` 分支）
* 等待 Review