<template>
    <section>
        <div class="features-text">
            <p class="small-slogan">luxury design</p>
            <h1 class="title">Perfect circles and</h1>
            <h1 class="title">Rectangles</h1>
            <p class="slogan">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unkno...</p>
        </div>
    </section>
</template>
<script>
export default {
       name:"Features",
       
}
</script>
<style lang="stylus" scoped>
section
  padding 0.8vw 6vw
  .features-text
   padding 10% 0
   max-width 55%
   .small-slogan
    color black
    text-transform uppercase
    color lighten(black,30)
   .title
    color black
    font-size 3rem
    font-weight bolder
    margin 1rem 0
  .slogan
    color black
    color lighten(black,30)
    line-height 1.5rem
</style>
