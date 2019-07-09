<template>
    <section>
        <div class="features-text">
            <p class="small-slogan">human beings</p>
            <h1 class="title">Our awesome staff</h1>
        </div>
        <grid class="wrapper">
            <row>
                <column :xs="12" :md="6">
                    <StaffCard />
                </column>
                <column :xs="12" :md="6">
                    <StaffCard class="active" />
                </column>
            </row>
        </grid>
    </section>
</template>
<script>
import StaffCard from '../components/StaffCard';
 export default {
     name:"Staff",
     components:{StaffCard}
 }
</script>
<style lang="stylus">
section
  padding 0.8vw 0vw
  .wrapper
    padding 0 8rem
  .features-text
   padding 10% 6rem
   max-width 55%
   .small-slogan
    color black
    text-transform uppercase
    color lighten(black,30)
   .title
    color black
    font-size 2.8rem
    font-weight bolder
    margin 1rem 0
  .slogan
    color black
    color lighten(black,30)
    line-height 1.5rem
</style>
