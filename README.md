## Mpvue-WeUI

mpvue-weui, 基于 mpvue 的 weui 框架,参考了mpvue-weui-dev,但因为业务不同，不能在其基础上拓展，所以自己写了个ui库。


## 安装

``` bash
npm install mpvue-weui --save  # cnpm install mpvue-weui-expand --save

```

## 使用
``` js
/* 全局引入 weui.css (在 `src/main.js` 中引入 weui.css) */
import 'mpvue-weui-expand/src/style/weui.css';
```
``` vue
<template>
  <mv-button type="primary" size="large" btnClass="mb15">默认按钮</mv-button>
</template>
<script>
  import mvButton from 'mpvue-weui/src/button';
  export default {
    components: {
      mvButton,
    },
  }
</script>
```

* 目前由于 `mpvue` 暂不支持全局安装组件，因此只能通过页面单独引入。


## 开发预览

``` bash
1. git clone
git clone git@github.com:tihumihu/mpvue-weui-expand.git

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
