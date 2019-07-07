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
        <div class="header-text">
          <p class="small-slogan">multipurpose</p>
          <h1 class="title">Corporate</h1>
          <h1 class="title">XD Template</h1>
          <p class="slogan">Will it be used for your home, your office or perhaps even your home office combo?</p>
        </div>
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
   padding 0.8rem 6rem
   nav
    ul
      display flex
      align-items center
      .logo
        flex-grow 1
        img
          height 32px
          width auto
      li
        display block
        margin 0 20px
</style>
