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
                  <i class="fab fa-html5"></i>
              </div>
              <div class="skill-text">

              </div>
          </div>
      </div>
    </div>
    <div class="skill-img">
      <img src="../assets/aftcfta.png" alt="" />
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

.skill-text{
    width: 300px;
}

.skill-img{
    width: 700px;
    height: 600px;
}

.skill-img img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}

.skill-heading span{
    color:#36b7b5;
    font-weight:500;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-size: 1rem;
}

.skill-heading h2{
    color: #1c3548;
    font-size: 2.5rem;
    margin: 0;
    font-weight: 600;
    letter-spacing: 1px;
}
</style>