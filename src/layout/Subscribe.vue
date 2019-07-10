<template>
    <section>
        <grid class="grid">
            <row class="row">
                <column :xs="12" :md="8">
                    <div class="input-wrapper">
                        <Input placeholder="example@nikandlv.ir" />
                        <Button>Subscribe</Button>
                    </div>
                </column>
                <column :xs="12" :md="4">
                    <h2>Subscribe to our news letter</h2>
                </column>
            </row>
        </grid>
    </section>
</template>
<script>
 import Input from '../components/Input'
 import Button from '../components/Button'
 export default {
     name:"Subscribe",
     components:{Input,Button}
 }
</script>
<style lang="stylus" scoped>
section
  background linear-gradient(45deg, #6c63ff 39%, #c77cf1 90%)
  margin-top 5rem
  .grid
    padding 3rem 8rem
    .row
        align-items center
        .input-wrapper
          display flex
        h2
          color white
        input
          white-space wrap
          flex-grow 1

</style>
