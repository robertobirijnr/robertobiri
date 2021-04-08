<template>
    <nav>
     <nuxt-link to="/">
      <span> Bob.</span>
     </nuxt-link>

     <!-- menu btn -->
     <input type="checkbox" class="menu-btn" id="menu-btn">
     <label for="menu-btn"  class="menu-icon">
       <span class="nav-icon"></span>
     </label>

     <ul class="menu">
       <li><nuxt-link to="/">Home</nuxt-link></li>
       <li><nuxt-link to="#skills">Skills</nuxt-link></li>
       <li><nuxt-link to="#recent">Recent Projects</nuxt-link></li>
       <li><nuxt-link to="#contact">Contact</nuxt-link></li>
     </ul>

     <nuxt-link class="hey" to="#contact">
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

input{
  display: none;
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

@media (max-width:900px){
  nav{
    justify-content: space-between;
    height: 65px;
    padding: 0px 30px;
  }

  .menu{
    display: none;
    position: absolute;
    top: 65px;
    left: 0px;
    background-color: #fff;
    border-bottom: 4px solid #1db096;
    width: 100%;
    padding: 0px;
    margin: 0px;
  }

  .menu li{
    width: 100%;
  }

  nav .menu li a{
    width: 100%;
    height: 40px;
    justify-content: center;
    align-items: center;
    margin: 0px;
    padding: 25px;
    border: 1px solid  rgba(38, 38, 38, 0.03);
  }

  nav .menu-icon{
    cursor: pointer;
    float: right;
    padding: 28px 20px;
    position: relative;
    user-select: none;
    margin-right: 3rem;
  }

  nav .menu-icon .nav-icon{
    background-color: #333333;
    display: block;
    height: 2px;
    position: relative;
    transition: background 0.2s ease-out;
    width: 18px;
  }

  nav .menu-icon .nav-icon:before,
  nav .menu-icon .nav-icon:after{
    background:#333333;
    content: "";
    display: block;
    height: 100%;
    position: absolute;
    transition: all ease-out 0.2s;
    width: 100%;
  }

  nav .menu-icon .nav-icon:before{
    top:5px;
  }

  nav .menu-icon .nav-icon:after{
    top: -5px;
  }

  nav .menu-btn:checked ~ .menu-icon .nav-icon{
    background-color: transparent;
  }

  nav .menu-btn:checked ~ .menu-icon .nav-icon:before{
    transform: rotate(-45deg);
    top: 0;
  }

   nav .menu-btn:checked ~ .menu-icon .nav-icon:after{
     transform: rotate(45deg);
     top: 0;
   }

   nav .menu-btn{
     display: none;
   }

    nav .menu-btn:checked ~ .menu{
      display: block;
    }
}
</style>