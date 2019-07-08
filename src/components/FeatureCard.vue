<template>
    <div class="feature-card">
        <h3><slot name="title">Lorem ipsum</slot></h3>
        <p><slot>The card content</slot></p>
    </div>
</template>
<script>
 export default {
     name:"FeatureCard"
 }
</script>
<style lang="stylus" scoped>
.feature-card
  background white
  transition box-shadow 300ms
  padding 2rem 4rem
  margin 10px
  text-align left
  &:hover
    -webkit-box-shadow 0px 0px 17px 0px rgba(0,0,0,0.20)
    -moz-box-shadow 0px 0px 17px 0px rgba(0,0,0,0.20)
    box-shadow 0px 0px 17px 0px rgba(0,0,0,0.20)

</style>
