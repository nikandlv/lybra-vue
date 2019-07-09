<template>
    <div class="quote">
        <div>
            <div class="wrapper">
                <div class="text-section">
                        <svg xmlns="http://www.w3.org/2000/svg" width="66.878" height="55.285" viewBox="0 0 66.878 55.285">
            <path id="Path_2" data-name="Path 2" d="M24.768-187.824q-1.391-1.391-2.782-2.836a21.943,21.943,0,0,1-2.461-3.05,15.664,15.664,0,0,1-1.766-3.638,14.171,14.171,0,0,1-.7-4.6,14.949,14.949,0,0,1,1.177-5.885A15.174,15.174,0,0,1,21.5-212.7a15.749,15.749,0,0,1,4.922-3.317,15.289,15.289,0,0,1,6.153-1.231,13.446,13.446,0,0,1,6.1,1.391,15.145,15.145,0,0,1,4.762,3.692,16.473,16.473,0,0,1,3.05,5.35,19.09,19.09,0,0,1,1.07,6.367,34.991,34.991,0,0,1-2.408,13.162,40.772,40.772,0,0,1-6.26,10.7,50.811,50.811,0,0,1-8.56,8.293,65.36,65.36,0,0,1-9.2,5.939q-1.5.856-2.3-.161t.7-2.622a26.375,26.375,0,0,0,4.066-5.35A27.058,27.058,0,0,0,26.32-176.8a16.868,16.868,0,0,0,.642-6.153A7.626,7.626,0,0,0,24.768-187.824Zm36.382,0q-1.391-1.391-2.782-2.836a21.943,21.943,0,0,1-2.461-3.05,15.664,15.664,0,0,1-1.766-3.638,14.171,14.171,0,0,1-.7-4.6,14.949,14.949,0,0,1,1.177-5.885,15.174,15.174,0,0,1,3.264-4.869,15.749,15.749,0,0,1,4.922-3.317,15.289,15.289,0,0,1,6.153-1.231,13.446,13.446,0,0,1,6.1,1.391,15.145,15.145,0,0,1,4.762,3.692,16.473,16.473,0,0,1,3.05,5.35,19.09,19.09,0,0,1,1.07,6.367,34.991,34.991,0,0,1-2.408,13.162,40.772,40.772,0,0,1-6.26,10.7,50.811,50.811,0,0,1-8.56,8.293,65.36,65.36,0,0,1-9.2,5.939q-1.5.856-2.3-.161t.7-2.622a26.375,26.375,0,0,0,4.066-5.35A27.058,27.058,0,0,0,62.7-176.8a16.868,16.868,0,0,0,.642-6.153A7.626,7.626,0,0,0,61.15-187.824Z" transform="translate(-17.064 217.25)" opacity="0.1"/>
        </svg>

                    <h2>Failure will never overtake me if my determination to succeed is strong enough</h2>
                    <h5>OG Mandino</h5>
                </div>
                <div class="avatar">
                    <img alt="OG Mandino" src="../assets/avatar.jpg" />
                 </div>
            </div>
</div>
    </div>
</template>
<script>
 export default {
     name:"quote"
 }
</script>
<style lang="stylus">
.quote
  position relative
  margin-top 16vh
  padding 1rem 8vw
  .wrapper
    display flex
    justify-content center
    align-items center
  .text-section
    width 37%
  svg
    display block
  .avatar
    img
        width 128px
        height 128px
        border-radius 100%
        border 2px solid gray
    position relative
    &:before
      content ''
      position absolute
      top -10px
      left -10px
      width 148px
      height 148px
      border 2px solid rgba(black,0.1)
      border-radius 100%
</style>
