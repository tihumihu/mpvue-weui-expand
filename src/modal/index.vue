<template>
  <div class="weui-dialog" v-show="modelShow">
    <div class="weui-dialog__hd" v-show="title"><strong class="weui-dialog__title">{{title}}</strong></div>
    <div class="weui-dialog__bd">
      <slot name="content"></slot>
    </div>
    <div class="weui-dialog__ft">
      <slot name="ft"></slot>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    modelShow: {
      type: Boolean,
      required: true,
      default: false
    },
    title: {
      type: String
    }
  }
};
</script>


