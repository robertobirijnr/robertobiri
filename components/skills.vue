<template>
  <section id="skills">
    <div class="skill-text">
      <div class="skill-heading">
        <span>My Skills</span>
        <h2>My Experties</h2>
      </div>

      <div class="skill-box-container">
        <div class="skill-box">
          <div class="icon">
            <i class="fab fa-js"></i>
          </div>
          <div class="skill-text">
            <strong>JavaScript</strong>
            <p>I have 2 years Expirence in JavaScript.</p>
          </div>
        </div>

        <div class="skill-box">
          <div class="icon">
            <i id="vue" class="fab fa-vuejs"></i>
          </div>
          <div class="skill-text">
            <strong>Vue js & Nuxt js</strong>
            <p>I have 2 years Expirence in JavaScript.</p>
          </div>
        </div>

        <div class="skill-box">
          <div class="icon">
            <i id="vue" class="fab fa-node-js"></i>
          </div>
          <div class="skill-text">
            <strong>Node Js</strong>
            <p>I have 2 years Expirence in JavaScript.</p>
          </div>
        </div>

        <div class="skill-box">
          <div class="icon">
            <i id="vue" class="fab fa-react"></i>
          </div>
          <div class="skill-text">
            <strong>React js & Next js</strong>
            <p>I have 2 years Expirence in JavaScript.</p>
          </div>
        </div>

        <div class="skill-box">
          <div class="icon">
            <i id="vue" class="fab fa-wordpress"></i>
          </div>
          <div class="skill-text">
            <strong>WordPress</strong>
            <p>I have 2 years Expirence in JavaScript.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="skill-img">
      <img src="../assets/afctfta.png" alt="" />
      <strong class="afcfta"
        >African Continental Free Trade Area (AfCFTA) Project</strong
      >
      <br />
      <a class="recent-btn" href="https://test.afcfta.app/" target="_blank">View Live</a>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style  scoped>
#skills {
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 90%;
  margin: auto auto 50px auto;
}

.skill-text {
  width: 300px;
}

.skill-img {
  width: 700px;
  height: 600px;
}

.skill-img img {
  width: 100%;
  padding-top: 9rem;
  object-fit: contain;
}

.skill-heading span {
  color: #36b7b5;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 1px;
  font-size: 1rem;
}

.skill-heading h2 {
  color: #1c3548;
  font-size: 2.5rem;
  margin: 0;
  font-weight: 600;
  letter-spacing: 1px;
}

.skill-box-container {
  margin-top: 30px;
}

.skill-box {
  display: flex;
  margin: 25px 0px;
}

.icon {
  margin-right: 12px;
}

.icon i {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #000;
  font-size: 1.1rem;
}

.icon #vue {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #f6efe8;
  font-size: 1.1rem;
}

.skill-text strong {
  color: #1c3548;
  margin: 0px;
  font-size: 0.9rem;
  font-weight: 600;
}

.skill-text p {
  color: #747474;
  font-size: 0.9rem;
}

.fa-js {
  color: yellow;
}

.fa-vuejs {
  color: green;
}

.afcfta {
  padding-left: 7rem;
  margin-top: 5rem;
}

.recent-btn {
  margin-left: 14rem;
  width: 190px;
  margin-top: 2rem;
  height: 40px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  background-color: #1c3548;
  border-radius: 20px;
  box-shadow: 4px 10px 30px rgba(24, 139, 119, 0.2);
}

a {
  text-decoration: none;
}
</style>