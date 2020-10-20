<!--
 * @Author: your name
 * @Date: 2020-10-20 16:06:43
 * @LastEditTime: 2020-10-20 20:29:32
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \music\src\components\HelloWorld.vue
-->
<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
<style lang="less" scoped>
@import url('~@/assets/style/base.less');
.hello{
  color: @color-theme;
}
</style>
