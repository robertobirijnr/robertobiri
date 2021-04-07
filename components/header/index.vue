<template>
    <section id="main">
        <the-nav-bar/>
        <hero-banner/>
    </section>
</template>

<script>
import HeroBanner from './Hero-banner.vue'
import TheNavBar from './TheNavBar.vue'
    export default {
  components: { TheNavBar,HeroBanner },
        
    }
</script>

<style scoped>
#main{
  width: 100%;
  height: 100vh;
  position: relative;
}
</style>