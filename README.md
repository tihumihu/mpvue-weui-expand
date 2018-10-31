## Mpvue-WeUI

mpvue-weui, 基于 mpvue 的 weui 框架,参考了mpvue-weui-dev,但因为业务不同，不能在其基础上拓展，所以自己写了个ui库。

## 文档

[mpvue-weui 文档](https://mpcomponent.github.io/mpvue-weui/)


## 扫码体验

<img src="https://user-images.githubusercontent.com/20694238/47097108-453cae00-d263-11e8-9cd6-5c7c41ad0678.jpg" width="200">


## 安装

``` bash
npm install mpvue-weui --save  # cnpm install mpvue-weui --save

```

## 使用
``` js
/* 全局引入 weui.css (在 `src/main.js` 中引入 weui.css) */
import 'mpvue-weui/src/style/weui.css';
```
``` vue
<template>
  <mp-button type="primary" size="large" btnClass="mb15">默认按钮</mp-button>
</template>
<script>
  import mpButton from 'mpvue-weui/src/button';
  export default {
    components: {
      mpButton,
    },
  }
</script>
```

* 目前由于 `mpvue` 暂不支持全局安装组件，因此只能通过页面单独引入。
* [更多组件](https://mpcomponent.github.io/mpvue-weui/)

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

## 相关说明
之前写了 [用 vue 写小程序，基于 mpvue 框架重写 weui](https://github.com/KuangPF/mpvue-weui),这个是在 mpvue 开源之初写的，开始的目的是想重写下 weui，然后写了一些踩坑文档。可能有点遗憾的是没有对其进行完整的封装，以至于在使用过程中就很不方便，在 issues 中也看到一些关于能不能封装成一个独立的 UI 框架的想法，加上大家也给了这个仓库这么多 ⭐️ ⭐️ ，因此决定将其封装成一个独立的 UI 框架：[mpvue-weui](https://github.com/MPComponent/mpvue-weui)。


## 贡献

欢迎各位大佬贡献代码，贡献方法如下：

* fork 本仓库到自己账户下
* 提交变更
* PR 到本仓库 （`dev` 分支）
* 等待 Review
