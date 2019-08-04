<template>
  <div class="m-header">
    <div class="icon"></div>
    <div class="text">Chicken Music</div>
  </div>
</template>

<script>
export default {
  name: 'm-header'
}
</script>

<style scoped lang="stylus">
  @import '~common/stylus/variable'
  @import '~common/stylus/mixin'

    .m-header
      position relative
      height 44px
      font-size 0
      text-align center
      color $color-theme

      .icon
        display inline-block
        margin-top 6px
        margin-right 9px
        width 30px
        height 32px
        bg-image('logo')
        background-size 30px 32px
        vertical-align top

      .text
        display inline-block
        font-size @font-size-large
        line-height 44px

      .mine
        position absolute
        top 0
        right 0

        .icon-mine
          display block
          padding 12px
          font-size 20px
          color $color-theme
</style>
