<template>
    <section>
        <div class="events-text">
            <p class="small-slogan">luxury design</p>
            <h1 class="title">Upcoming Events</h1>
            <p class="slogan">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unkno...</p>
        </div>
        <grid center="xs" class="events">
            <row>
                <column :xs="12" :md="6">
                    <EventCard class="active">

                    </EventCard>
                </column>
                <column :xs="12" :md="6">
                    <EventCard>

                    </EventCard>
                </column>
                <column :xs="12" :md="6">
                    <EventCard>

                    </EventCard>
                </column>
                <column :xs="12" :md="6">
                    <EventCard>

                    </EventCard>
                </column>
                <column :xs="12" :md="6">
                    <EventCard>

                    </EventCard>
                </column>
                <column :xs="12" :md="6">
                    <EventCard>

                    </EventCard>
                </column>
            </row>
        </grid>
    </section>
</template>
<script>
 import EventCard from '../components/EventCard';
 export default {
     name:"Events",
     components:{EventCard}
 }
</script>
<style lang="stylus" scoped>
@media(max-width:800px)
  .events
    padding 3rem
.events
 padding 0 6rem
.events-text
   padding 10% 6rem 3% 6rem
   max-width 45%
   .small-slogan
    color black
    text-transform uppercase
    color lighten(black,30)
   .title
    color black
    font-size 2.7rem
    font-weight bolder
    margin 1rem 0
  .slogan
    color black
    color lighten(black,30)
    line-height 1.5rem
</style>

