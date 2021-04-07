<template>
    <nav>
     <nuxt-link to="/">
      <span> Bob.</span>
     </nuxt-link>

     <ul class="menu">
       <li><nuxt-link to="/">Home</nuxt-link></li>
       <li><nuxt-link to="/">Skills</nuxt-link></li>
       <li><nuxt-link to="/">Recent Projects</nuxt-link></li>
       <li><nuxt-link to="/">Contact</nuxt-link></li>
     </ul>

     <nuxt-link class="hey" to="/">
       Say Hi
     </nuxt-link>
   </nav>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

ul{
  list-style: none;
}

a{
  text-decoration: none;
}

nav{
  display: flex;
  justify-content: space-around;
  align-items: center;
  box-shadow: 5px 10px 30px rbga(0,0,0,0.02);
  position: fixed;
  left: 0;
  top:0;
  width: 100%;
  z-index: 1; 
  background-color: #fff;
}

nav ul{
  display: flex;
}

nav ul li a{
  height: 40px;
  line-height: 43px;
  margin: 3px;
  padding: 0px 22px;
  display: flex;
  font-size: 0.8rem;
  text-transform: uppercase;
  font-weight: 500;
  color: #585b5b;
  letter-spacing: 1px;
}

.hey{
  color: #39bfbd;
  font-weight: 500;
  font-size: 0.9rem;
  border-bottom:2px solid #40c6c4
}

nav ul li a:hover{
  background-color: #2adabc;
  color: #fff;
  box-shadow: 5px 10px 30px rgba(64,198,196,0.3);
  transition: all ease 0.2s;
}

span{
    font-size: 40px;
    font-weight: 700;
    color: #2adabc;
}
</style>