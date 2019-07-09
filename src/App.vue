<template>
    <div>
        <Header />
        <Features />
        <Preview />
        <Events />
        <Quote />
        <Staff />
      </div>
</template>
<script>
 import Header from './layout/Header';
 import Features from './layout/Features';
 import Preview from './layout/Preview';
 import Events from './layout/Events';
 import Quote from './layout/Quote';
 import Staff from './layout/Staff';
 export default {
     name: "app",
      components: {
          Header,
          Features,
          Preview,
          Events,
          Quote,
          Staff
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
