# Switch

开关选择器，使用原生的 switch 组件，支持数据双向绑定。

<imgPreview imgUrl="/assets/switch.png"/>

### 引入

``` js
import mpSwitch from 'mpvue-weui/src/switch';
export default {
  components: {
    mpSwitch,
  },
}
```

### 使用

``` html
<!-- 数据双向绑定 -->
<mp-switch v-model="switchValue" @change="switchChange"></mp-switch>
<!-- 禁用状态 -->
<mp-switch :disabled=true></mp-switch>
```

### API

| 参数 | 说明 | 类型 | 默认值 |
|-----------|-----------|-----------|-------------|
| value | `switch` 是否选中，可使用 v-model 双向绑定数据。 | `Boolean` | `false` |
| disabled | 是否禁用 | `Boolean` | `false` |
| color | `switch` 的颜色，同 css 的 color | `String` | `-` |


### Event
| 事件名 | 说明 | 参数 |
|-----------|-----------|-----------|
| @change| 改变时触发 | 返回是否选中 `true` , `false` |

