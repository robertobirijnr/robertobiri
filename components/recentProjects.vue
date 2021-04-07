<template>
  <section id="recent">
    <h2>My Projects</h2>
    <!-- <div class="recent-heading">
            <span>Recent</span>
            <h3>Recent Doing Projects</h3>
        </div> -->
    <div class="recent-img">
      <img src="../assets/codeboothonline.png" alt="" />
    </div>
    <strong>codeBooth Africa</strong>
    <p>African number one online learning platform</p>
    <a class="recent-btn" target="_blank" href="https://github.com/robertobirijnr/udemy-clone">View Project</a>

    
  </section>
</template>

<script>
export default {};
</script>

<style  scoped>
#recent {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 30px 0px;
  flex-direction: column;
}

.recent-heading span {
  color: #36b7b5;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 2px;
  font-size: 1.1rem;
}

.recent-heading h3 {
  color: #1c3548;
  font-size: 3rem;
  margin: 0px;
  font-weight: 400;
  letter-spacing: 1px;
}

.recent-img {
  margin: 0px 10px;
}

.recent-img img {
  width: 100%;
  height: 100%;
}

a {
  text-decoration: none;
}

.recent-btn {
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
  margin-top: 10px;
}

h2 {
  color: #1c3548;
  font-size: 2.5rem;
  margin: 0;
  font-weight: 600;
  letter-spacing: 1px;
  margin-bottom: 3rem;
}
</style>