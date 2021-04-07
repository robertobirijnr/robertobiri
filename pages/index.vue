<template>
 <section id="main">
  <the-nav-bar/>
  <hero-banner/>
 </section>
</template>

<script>
import HeroBanner from '../components/Hero-banner.vue'
import TheNavBar from '../components/TheNavBar.vue'
export default {
  components: { TheNavBar,HeroBanner },}
</script>

<style>

#main{
  width: 100%;
  height: 100vh;
  position: relative;
}




</style>
