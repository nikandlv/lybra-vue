<template>
    <div class="card">
        <div class="image">
            <slot name="image">
                <img alt="holder" src="../assets/post-1.png"/>
            </slot>
        </div>
        <div class="head">
            <div class="date">
                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="20" viewBox="0 0 18 20">
                    <path id="ic_date_range_24px" d="M9,11H7v2H9Zm4,0H11v2h2Zm4,0H15v2h2Zm2-7H18V2H16V4H8V2H6V4H5A1.991,1.991,0,0,0,3.01,6L3,20a2,2,0,0,0,2,2H19a2.006,2.006,0,0,0,2-2V6A2.006,2.006,0,0,0,19,4Zm0,16H5V9H19Z" transform="translate(-3 -2)"/>
                </svg>
                <p>
                    <slot name="date">10 FEB 2019</slot>
                </p>
            </div>
            <div class="title">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
                    <path id="ic_perm_identity_24px" d="M12,5.9A2.1,2.1,0,1,1,9.9,8,2.1,2.1,0,0,1,12,5.9m0,9c2.97,0,6.1,1.46,6.1,2.1v1.1H5.9V17c0-.64,3.13-2.1,6.1-2.1M12,4a4,4,0,1,0,4,4A4,4,0,0,0,12,4Zm0,9c-2.67,0-8,1.34-8,4v3H20V17C20,14.34,14.67,13,12,13Z" transform="translate(-4 -4)"/>
                </svg>
                <p>
                    <slot name="title">Staff</slot>
                </p>
            </div>
        </div>
        <h2 class="post-title">
            <slot>no details available</slot>
        </h2>
        <a href="#">Read more</a>
    </div>
</template>
<script>
 export default {
     name:"PostCard"
 }
</script>
<style lang="stylus">
.card
  background white
  box-shadow 0 0 17px 0 rgba(0,0,0,0.2)
  padding-bottom 2rem
  .head
    display flex
    padding 1rem 2rem
    .date,.title
      display flex
      align-items center
      p
        margin 10px
    .date
      flex-grow 1
  .post-title,a
    padding 1rem 2rem
    
  a
    color #6c63ff
    text-decoration unset
    outline unset
  .image
    width 100%
    position relative
    &:before
      content ''
      width 100%
      height 100%
      position absolute
      top 0
      left 0
      background linear-gradient(0deg,rgba(#c77cf1,0.4),rgba(#6c63ff,0.4))
    img
      width 100%
      height auto
      display block
</style>
