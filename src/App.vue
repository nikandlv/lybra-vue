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
@import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');
@import '../node_modules/normalize-stylus/normalize.styl'
body
 background-color white
 font-family 'Montserrat', sans-serif
 overflow-x hidden

</style>
