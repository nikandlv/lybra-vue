<template>
    <header>
        <img alt="Lybra" src="../assets/logo.png"/>
        <nav>
            <ul>
                <li><Link to="#" text="test" /></li>
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
