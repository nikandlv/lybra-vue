<template>
  <button><slot>Button</slot></button>
</template>
<script>
 export default {
     name:"Button"
 }
</script>
<style lang="stylus" scoped>
button
  background linear-gradient(45deg, #ee7a37 30%, #fddb71 90%);
  color white
  font-weight bold
  text-transform uppercase
  padding 1rem
  letter-spacing 4px
  border unset
  outline unset
  cursor pointer
  position relative
  overflow hidden
  font-size 0.7rem
  &:before
    content ''
    position absolute
    top 0
    left -10%
    width 50%
    height 100%
    background rgba(0,0,0,0.05)
    transform skew(30deg, 0deg)
</style>
