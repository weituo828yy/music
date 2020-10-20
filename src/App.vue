<!--
 * @Author: your name
 * @Date: 2020-10-20 16:06:43
 * @LastEditTime: 2020-10-20 20:48:33
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \music\src\App.vue
-->
<template>
  <div id="app">
    <m-header></m-header>
    <router-view/>
  </div>
</template>

<script>
import MHeader from '@/components/m-header/m-header'
export default {
  name: 'App',
  components: {
    MHeader
  }
}
</script>

<style lang="less" scoped>
</style>
