<template>
    <grid center="xd" class="preview-wrapper">
        <row>
            <column :xs="12" :lg="6">
                <div class="preview-text">
                    <p class="small-slogan">You should to see</p>
                    <h1 class="title">Carefuly crafted with love to small things</h1>
                    <p class="slogan">Will it be used for your home, your office or perhaps even your home office combo?</p>
                    <Button>Contact me</Button>
                </div>
            </column>
            <column :xs="12" :lg="6">
                testssssssss
            </column>
        </row>
    </grid>
</template>
<script>
import Button from '../components/Button'
 export default {
     name:"Preview",
     components:{Button}
 }
</script>
<style lang="stylus" scoped>
.preview-wrapper
  padding 0
  .preview-text
    padding 10% 0
    max-width 45%
    .small-slogan
      color black
      text-transform uppercase
      color lighten(black,30)
    .title
      color black
      font-size 2.7rem
      font-weight bolder
      margin 1rem 0
    .slogan
      color black
      font-weight bold

</style>
