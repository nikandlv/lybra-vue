<template>
    <header>
        <nav>
            <ul>
                <li class="logo"><img alt="Lybra" src="../assets/logo.png"/></li>
                <li><Link to="#" text="Demos" /></li>
                <li><Link to="#" text="Pages" /></li>
                <li><Link to="#" text="Elements" /></li>
                <li><Link to="#" text="Blog" /></li>
                <li><Link to="#" text="Contact" /></li>
            </ul>
        </nav>
    </header>
</template>
<script>
 import Link from '../components/Link'
 export default {
     name:"Header",
     components:{Link}
 }
</script>
<style lang="stylus">
 header
   padding 1rem 6rem
   nav
    ul
      display flex
      .logo
        flex-grow 1
        img
          height 32px
          width auto
      li
        display block
        margin 0 20px
</style>
