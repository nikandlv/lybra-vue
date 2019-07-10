<template>
    <section>
        <div class="staff-text">
            <p class="small-slogan">human beings</p>
            <h1 class="title">Our awesome staff</h1>
        </div>
        <grid class="wrapper">
            <row>
                <column :xs="12" :md="6">
                    <StaffCard name="Leron Walton" title="Chief Analytics Officer">
                        <template v-slot:image>
                            <img alt="Leron Walton" src="../assets/staff-1.png" />
                        </template>
                    </StaffCard>
                </column>
                <column :xs="12" :md="6">
                    <StaffCard name="Leron Walton" title="Chief Analytics Officer">
                        <template v-slot:image>
                            <img alt="Leron Walton" src="../assets/staff-2.png" />
                        </template>
                    </StaffCard>
                </column>
                <column :xs="12" :md="6">
                    <StaffCard name="Leron Walton" title="Chief Analytics Officer">
                        <template v-slot:image>
                            <img alt="Leron Walton" src="../assets/staff-3.png" />
                        </template>
                    </StaffCard>
                </column>
                <column :xs="12" :md="6">
                    <StaffCard name="Leron Walton" title="Chief Analytics Officer" class="active">
                        <template v-slot:image>
                            <img alt="Leron Walton" src="../assets/staff-4.png" />
                        </template>
                    </StaffCard>
                </column>
                <column :xs="12" :md="6">
                    <StaffCard name="Leron Walton" title="Chief Analytics Officer">
                        <template v-slot:image>
                            <img alt="Leron Walton" src="../assets/staff-5.png" />
                        </template>
                    </StaffCard>
                </column>
                <column :xs="12" :md="6">
                    <StaffCard name="Leron Walton" title="Chief Analytics Officer">
                        <template v-slot:image>
                            <img alt="Leron Walton" src="../assets/staff-1.png" />
                        </template>
                    </StaffCard>
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
<style lang="stylus" scoped>
@media(max-width:800px)
  section
    .wrapper
      padding 0 1rem !important
    .staff-text
      max-width 100% !important
      padding 8% 5% !important
section
  padding 0.8vw 0vw
  .wrapper
    padding 0 8rem
  .staff-text
   padding 2% 6rem
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
