<template>
  <page-content title="uploader" desc="图片上传组件，基于 `wx.chooseImage` 和 `wx.previewImage` 实现。">
    <mv-uploader @upLoadSuccess="upLoadSuccess" @upLoadFail="upLoadFail" @upLoadComplete="upLoadComplete" @uploadDelete="uploadDelete" :showTip="true" :count=10 :showDesc=true :showVoice=true></mv-uploader>
  </page-content>
</template>

<script>
import mvUploader from '../../../src/uploader';
import pageContent from '../../components/page-content';
export default {
  components: {
    mvUploader,
    pageContent
  },
  methods: {
    upLoadSuccess(res) {
      console.log(res);
    },
    upLoadFail(res) {
      console.log(res);
    },
    upLoadComplete() {
      console.log('complete');
    },
    uploadDelete(res) {
      console.log(res);
    }
  }
};
</script>

<style>
</style>
