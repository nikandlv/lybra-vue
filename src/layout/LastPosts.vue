<template>
    <section>
        <div class="last-post-text">
            <p class="small-slogan">publication</p>
            <h1 class="title">Latest posts</h1>
            <p class="slogan">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unkno...</p>
        </div>
        <grid center="xs">
            <row>
                <column :xs="12" :md="6" lg="4">
                    
                </column>
                <column :xs="12" :md="6" lg="4">
                    
                </column>
                <column :xs="12" :md="6" lg="4">
                    
                </column>
            </row>
        </grid>
    </section>
</template>
<script>
 export default {
     name:"LastPosts"
 }
</script>
<style lang="stylus" scoped>
section
 padding 0.8vw 0vw
.last-post-text
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
