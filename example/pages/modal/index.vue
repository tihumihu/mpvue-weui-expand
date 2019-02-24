<template>
  <div class="weui-cells">
    <div class="weui-cell">
      <a @click="showModal" class="weui-btn weui-btn_default">+ 添加章节</a>
    </div>
    <div class="weui-cell" >
      <div class="weui-cell__bd weui-dialog">
        <v-modal :title="添加章节" :modelShow="modalShow" >
          <div slot="content">
            content
          </div>
          <div class="weui-dialog__ft" slot="ft">
            <a href="javascript:;" class="weui-dialog__btn weui-dialog__btn_default">辅助操作</a>
            <a href="javascript:;" class="weui-dialog__btn weui-dialog__btn_primary">主操作</a>
          </div>
        </v-modal>
      </div>
    </div>
  </div>
</template>

<script>
import vModal from '../../../src/modal';
export default {
  data() {
    return {
      title: '标题',
      content: '内容',
      modalShow:false
    };
  },
  components: {
    vModal
  },
  methods: {
    showModal() {
      this.modalShow =true;
    },
    confirm(res) {
      console.log(res);
      console.log('confirm');
    },
    cancel(res) {
      console.log(res);
      console.log('cancel');
    },
    fail(res) {
      console.log(res);
      console.log('fail');
    },
    complete(res) {
      console.log(res);
      console.log('complete');
    }
  }
};
</script>

<style scoped>
</style>
