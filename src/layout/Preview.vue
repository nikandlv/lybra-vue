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
            <div class="preview-card">
                <svg class="play-button" xmlns="http://www.w3.org/2000/svg" width="46.084" height="45.969" viewBox="0 0 46.084 45.969">
                    <path id="ic_slow_motion_video_24px" d="M27.46,19.929l-7.045-5.29v20.79l7.045-5.29,6.814-5.105Zm0,0-7.045-5.29v20.79l7.045-5.29,6.814-5.105Zm0,0-7.045-5.29v20.79l7.045-5.29,6.814-5.105ZM22.724,6.716V2.05A22.982,22.982,0,0,0,10.435,7.155l3.28,3.3A18.344,18.344,0,0,1,22.724,6.716Zm-12.266,7-3.3-3.28A22.982,22.982,0,0,0,2.05,22.724H6.716a18.344,18.344,0,0,1,3.742-9.009ZM6.716,27.344H2.05A22.982,22.982,0,0,0,7.155,39.634l3.3-3.3a18.175,18.175,0,0,1-3.742-8.986Zm3.719,15.569a23.057,23.057,0,0,0,12.289,5.105V43.353a18.344,18.344,0,0,1-9.009-3.742l-3.28,3.3Zm37.7-17.879A23.135,23.135,0,0,1,27.46,48.019V43.353a18.478,18.478,0,0,0,0-36.637V2.05A23.135,23.135,0,0,1,48.134,25.034Z" transform="translate(-2.05 -2.05)" fill="#fff"/>
                </svg>
            </div>
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
@media(max-width:800px)
  .preview-wrapper
    padding 1rem !important
  .preview-text
    max-width 100% !important
.preview-wrapper
  padding 1rem 6rem
  .preview-card
    background #6c63ff
    width 100%
    height 100%
    min-height 400px
    position relative
    .play-button
      position absolute
      top 0
      left 0
      bottom 0
      right 0
      margin auto
      cursor pointer
  .preview-text
    padding 10% 0
    max-width 70%
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
