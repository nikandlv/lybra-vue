<template>
    <div class="card">
        <slot name="image"></slot>
        <div class="text-section">
           <p>{{name}}</p>
           <span>{{title}}</span>
        </div>
    </div>
</template>
<script>
 export default {
     name:"StaffCard",
     props:["name","title"]
 }
</script>
<style lang="stylus" scoped>
.card
  display flex
  margin 10px
  border 1px solid #ebebeb
  .text-section
    padding 1rem 4rem
    font-size 1.3rem
    white-space nowrap
    p
      font-weight bold
  &.active
    background linear-gradient(45deg, #6c63ff 39%, #c77cf1 90%)
    .text-section
      p,span
            color white

</style>
