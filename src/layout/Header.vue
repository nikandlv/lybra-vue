<template>
    <header>
      <HeaderArt />
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
          <div class="contact-wrapper">
            <Input placeholder="+98 09 300" />
            <Button>Contact me</Button>
          </div>
        </div>
      </header>
  </template>
  <script>
import Link from '../components/Link'
import HeaderArt from './art/HeaderArt'
import Input from '../components/Input';
import Button from '../components/Button';
 export default {
     name:"Header",
     components:{Link,HeaderArt,Input,Button}
 }
</script>
<style lang="stylus">
 header
  padding 0.8vw 6vw
  position relative
  nav
   ul
     display flex
     overflow-x auto
     align-items center
     .logo
       flex-grow 1
       img
         height 32px
         width auto
     li
       display block
       margin 0 20px
 .header-text
  padding 10% 0
  max-width 45%
  .small-slogan
   color black
   text-transform uppercase
  .title
   color black
   font-size 3rem
   font-weight bolder
   margin 1rem 0
  .slogan
   color black
   font-weight bold
 .contact-wrapper
   display flex
   margin-top 32px
</style>
