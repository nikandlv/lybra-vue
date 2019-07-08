<template>
    <section>
        <div class="features-text">
            <p class="small-slogan">luxury design</p>
            <h1 class="title">Perfect circles and</h1>
            <h1 class="title">Rectangles</h1>
            <p class="slogan">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unkno...</p>
        </div>
        <grid class="features">
            <row center="xs">
                <column :xs="12" :sm="6" :md="4">
                    <FeatureCard>
                        <template v-slot:title>Easy Interface</template>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since
                    </FeatureCard>
                </column>
                <column :xs="12" :sm="6" :md="4">
                    <FeatureCard>
                        <template v-slot:title>Shortcode Manager</template>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since
                    </FeatureCard>
                </column>
                <column :xs="12" :sm="6" :md="4">
                    <FeatureCard>
                        <template v-slot:title>Solid Code</template>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since
                    </FeatureCard>
                </column>
                <column :xs="12" :sm="6" :md="4">
                    <FeatureCard>
                        <template v-slot:title>Premium Design</template>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since
                    </FeatureCard>
                </column>
                <column :xs="12" :sm="6" :md="4">
                    <FeatureCard>
                        <template v-slot:title>Favorites</template>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since
                    </FeatureCard>
                </column>
                <column :xs="12" :sm="6" :md="4">
                    <FeatureCard>

                        <template v-slot:title>Updates</template>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since
                    </FeatureCard>
                </column>
            </row>
        </grid>
    </section>
</template>
<script>
 import FeatureCard from '../components/FeatureCard'
 export default {
     name:"Features",
     components:{FeatureCard}
}
</script>
<style lang="stylus" scoped>
section
  padding 0.8vw 0vw
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
 .features
  padding 0 5rem
</style>
