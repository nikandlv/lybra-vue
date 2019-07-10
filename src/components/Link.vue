<template>
    <a :href="to">{{text}}</a>
</template>
<script>
 export default {
     name:"Link",
     props:[
         "to",
         "text"
     ]
 }
</script>
<style lang="stylus" scoped>
 a
  text-decoration none
  color black
  font-weight bold
  font-size 0.9rem
  transition color 300ms
  &:hover,&:focus,&:active
    color #6c63ff

 
</style>
