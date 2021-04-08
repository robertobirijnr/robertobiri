<template>
  <section id="contact">
    <div class="contact-heading">
      <span>Contact</span>
      <h2>Let's connect.</h2>
      <p>robertobirijnr@gmail.com</p>
    </div>

    <div class="message">
      <div class="contact-text">
        <button class="btn"><a href="https://github.com/robertobirijnr" target="_blank">Github</a></button>
        <button class="btn"><a href="https://www.linkedin.com/in/robert-obiri-jnr-0a92aa141" target="_blank">LinkedIn</a></button>
        <button class="btn"><a href="https://twitter.com/alaska_jnr" target="_blank">Twitter</a></button>
    </div>
    </div>
    <span class="copyright">
      <h5>Robert Obiri Jnr. &#169; 2021</h5>
    </span>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.contact-heading {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding-top: 2rem;
}
.contact-heading span {
  color: #36b7b5;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 1px;
  font-size: 1rem;
}

.contact-heading h2 {
  color: #1c3548;
  font-size: 2.5rem;
  margin: 0;
  font-weight: 700;
  letter-spacing: 1px;
}

#contact {
  width: 100%;
  padding: 50px 0px;
  border-top: 1px solid rgba(58, 58, 58, 0.03);
  border-bottom: 1px solid rgba(58, 58, 58, 0.03);
  background: url("../assets/bg.png");
  background-size: 1000px;
  background-position: center;
}

.contact-text {
  display: flex;
  justify-content: center;
  align-items: center;
}

.btn {
  width: 200px;
  height: 60px;
  background: none;
  border: 4px solid;
  color: #1c3548;
  font-weight: 700;
  margin-right: 0.5rem;
  margin-top: 1rem;
  cursor: pointer;
  font-size: 1.6rem;
}

a {
  text-decoration: none;
  color: #1c3548;
}

p {
  color: #747474;
  font-size: 0.9rem;
  font-weight: 300;
  font-family: "Poppin" sans-serif;
}

.copyright {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 2rem;
  color: #1c3548;
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 1px;
}

@media (max-width:720px){
  .contact-text{
    margin-left: 2rem;
  }
}
</style>