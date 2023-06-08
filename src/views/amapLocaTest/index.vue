<template>
  <div class="amapLocaTestView">
    <h2>高德地图Loca测试</h2>
    <!-- eslint-disable-next-line vue/attribute-hyphenation -->
    <amap-view styleId="6b11188d6c2ef3c4220097ae97dac30e" :zoom="13">
      <amap-loca-point />
    </amap-view>
  </div>
</template>

<script>
import indexjs from './index.js'
export default {
  ...indexjs
}
</script>

<style lang='scss' scoped>
@import './index.scss'
</style>
