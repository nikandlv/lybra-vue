<template>
    <section>
        <div class="last-post-text">
            <p class="small-slogan">publication</p>
            <h1 class="title">Latest posts</h1>
            <p class="slogan">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unkno...</p>
        </div>
        <grid center="xs" class="posts">
            <row>
                <column :xs="12" :md="6" :lg="4">
                    <PostCard>
                        <template v-slot:image>
                            <img alt="Post 1" src="../assets/post-1.png"/>
                        </template>
                        <template v-slot:date>13 NOV 2018</template>
                        <template v-slot:title>CTO</template>
                        Improve your communication skills with 3 simple methods
                    </PostCard>
                </column>
                <column :xs="12" :md="6" :lg="4">
                    <PostCard>
                        <template v-slot:image>
                            <img alt="Post 2" src="../assets/post-2.png"/>
                        </template>
                        <template v-slot:date>7 FEB 2019</template>
                        <template v-slot:title>CEO</template>
                        Heres the latest update on our startup company and the patch notes
                    </PostCard>
                </column>
                <column :xs="12" :md="6" :lg="4">
                    <PostCard>
                        <template v-slot:image>
                            <img alt="Post 1" src="../assets/post-3.png"/>
                        </template>
                        <template v-slot:date>21 DEC 2019</template>
                        <template v-slot:title>CPM</template>
                        How we improve our products as we progress and go on
                    </PostCard>
                </column>
            </row>
        </grid>
    </section>
</template>
<script>
 import PostCard from '../components/PostCard';
 export default {
     name:"LastPosts",
     components:{
         PostCard
     }
 }
</script>
<style lang="stylus" scoped>
@media(max-width:800px)
  .last-post-text
    padding 5% 2rem !important
    max-width 100% !important
  .posts
    padding 1rem !important
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
.posts
 padding 1rem 6rem
</style>
