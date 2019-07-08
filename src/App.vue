<template>
    <div>
        <Header />
        <Features />
        <Preview />
      </div>
</template>
<script>
 import Header from './layout/Header';
 import Features from './layout/Features';
 import Preview from './layout/Preview';
 export default {
     name: "app",
      components: {
          Header,
          Features,
          Preview
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
