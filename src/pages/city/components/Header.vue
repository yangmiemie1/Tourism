<template>
    <div class="header">
        城市选择
        <router-link to="/">
            <div class="iconfont header-back">&#xe611;</div>
        </router-link>
    </div>
</template>

<script>
export default {
  name: 'CityHeader'
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .header
    position: relative
    overflow: hidden
    height: $headerHeight
    line-height: $headerHeight
    color: #ffffff
    text-align: center
    background: $bgColor
    font-size: .32rem
    .header-back
      top: 0
      left: 0
      position:absolute
      width: .64rem
      text-align: center
      font-size: .4rem
      color: #fff
</style>
