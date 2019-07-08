<template>
    <div>
        <Header />
        <Features />
      </div>
</template>
<script>
 import Header from './layout/Header';
 import Features from './layout/Features';
 export default {
     name: "app",
      components: {
          Header,
          Features
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
