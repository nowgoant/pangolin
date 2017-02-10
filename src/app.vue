<template>
  <div class="content">
    <h1>pangolin</h1>
    <p>A vue hi.</p>
    <el-button>默认按钮</el-button>
  </div>
</template>
<script>
  import Vue from 'vue';
  import {
    Button
  } from 'element-ui';

  Vue.use(Button);
  console.log('hihi');
  export default {
    name: 'app'
  };
</script>
<style scoped>
  .content {
    font-size: 12px;
  }
</style>