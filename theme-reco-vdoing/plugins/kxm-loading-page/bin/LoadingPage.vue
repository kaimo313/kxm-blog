<template>
  <div class="global-loading-wrapper">
    <div class="loader-main">
      <img :src="require('../../../images/loading.jpg')" alt="loading">
    </div>
  </div>
</template>

<style lang="stylus" scoped>
.global-loading-wrapper
  position fixed
  z-index 99999
  top 0
  bottom 0
  left 0
  right 0
  margin auto
  height 100vh
  width 100vw
  background #f5f3ef
  text-align center
  cursor url(/blogs/cursor.ico), auto !important
  &::after
    content ""
    display inline-block
    height 100%
    width 0
    vertical-align middle
  .loader-main
    display inline-block
    vertical-align middle
    img
      width 18rem
</style>
