<template>
  <section class="hero">
    <div class="hero-image">
      <img src="~/assets/robert.png" alt="" />
    </div>
    <div class="hero-text">
      <h1>Hello, I am Robert</h1>
      <p>
        I'm a passionate Frontend Web Developer using web technologies to build
        amazing products and focusing on solving problems for different niches
        and different industries using the power of technology.
      </p>

      <nuxt-link to="#" class="port-btn">Download My CV</nuxt-link>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style  scoped>
.hero-image img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

img {
  border-radius: 50%;
  
}

.hero-image {
  width: 500px;
  height: 500px;
}

a {
  text-decoration: none;
}

.hero {
  width: 90%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}

.hero-text {
  width: 500px;
}

.hero-text h1 {
  font-size: 3.5rem;
  color: #1c3548;
  margin: 0px 0px 10px 0px;
  line-height: 60px;
}

.hero-text p {
  color: #747474;
}

.port-btn {
  width: 190px;
  height: 44px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  background-color: #1db096;
  border-radius: 20px;
  box-shadow: 4px 10px 30px rgba(24, 139, 119, 0.2);
  margin-top: 10px;
}

.port-btn:hover {
  background-color: #23cdaf;
  transition: all ease 0.2s;
}
</style>