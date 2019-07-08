<template>
    <div class="event">
        <svg class="expand-icon" xmlns="http://www.w3.org/2000/svg" width="15.8" height="9.756" viewBox="0 0 15.8 9.756">
            <path id="ic_keyboard_arrow_down_24px" d="M7.856,7.84,13.9,13.87l6.043-6.03L21.8,9.7l-7.9,7.9L6,9.7Z" transform="translate(-6 -7.84)"/>
        </svg>
        <p>Sunday,25 September 2019</p>
        <span>12:00AM</span>
    </div>
</template>
<script>
 export default {
     name:"EventCard"
 }
</script>
<style lang="stylus" scoped>
.event
  display flex
  align-items center
  -webkit-box-shadow 0px 0px 17px 0px rgba(0,0,0,0.20)
  -moz-box-shadow 0px 0px 17px 0px rgba(0,0,0,0.20)
  box-shadow 0px 0px 17px 0px rgba(0,0,0,0.20)
  padding 1rem 2rem
  margin 0.7rem 0
  cursor pointer
  &.active
    box-shadow unset
    background linear-gradient(45deg, #6c63ff 39%, #c77cf1 90%)
    .expand-icon
      fill white
    p
      color white
  span
    color black
    background white
    border-radius 8px
    padding 0.7rem 1.4rem
    font-weight bold
  p
    flex-grow 1
    padding 0 3vw
    font-weight bold
  .expand-icon
    display block
</style>
