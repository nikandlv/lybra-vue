<template>
    <header>
        <img alt="Lybra" src="../assets/logo.png"/>
        <nav>
            <ul>
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
   padding 4rem
</style>
