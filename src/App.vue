<template>
    <div>
        <Header />
    </div>
</template>
<script>
 import Header from './layout/Header';
 export default {
     name: "app",
     components: {
         Header 
     }

 }
</script>
<style lang="stylus">
@import '../node_modules/normalize-stylus/normalize.styl'
body
 background-color white

</style>
