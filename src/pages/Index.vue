<template>
  <div class="content">
    <header>
      <img class="logo" src="../../static/imges/logo.332701b7.svg" alt="Nichlas W. Andersen" width="60">
      <div class="nav-right"> Journal &nbsp;&nbsp;&nbsp;&nbsp; Say Hi! </div>
    </header>
    <div class="container">
      <div class="hero">
        <div class="hero-title" style="font-size:3rem; font-weight: 700;">Simplicity.</div>
        <div class="hero-title" style="font-size:3rem; font-weight: 700;">Aesthetics. Value.</div>
        <div class="hero-subtitle" style="font-size:1.2rem;color: gray;margin-top: 20px;">Hi there, I'm an independent Digital Designer &amp; Art Director focused on
          digital design for brands that like to have fun.</div>
      </div>
      <div class="projects">
        <div class="project project1">
          <img alt="Banana" src="../../static/imges/banana.jpg" class="pic pic1"></img>
          <h3 class="project-title">Banana</h3>
          <span class="category">photography &nbsp; pink</span>
        </div>
        <div class="projects2">
          <div class="project project2">
            <img alt="Pineapple" src="../../static/imges/pineapple.jpg" class="pic pic2">
            <h3 class="project-title">Pineapple</h3>
            <span class="category">photography &nbsp; blue</span>
          </div>
          <div class="project project3">
            <img alt="Ice Cream" src="../../static/imges/ice-cream.jpg" class="pic pic3">
            <h3 class="project-title">Ice Cream</h3>
            <span class="category">photography &nbsp; yellow</span>
          </div>
        </div>
        <div class="project project4">
          <img alt="Porta400" src="../../static/imges/porta400.jpg" class="pic pic4">
          <h3 class="project-title">Porta400</h3>
          <span class="category">photography &nbsp; yellow</span>
        </div>
      </div>
      <div class="label" style="font-weight: 700;font-size: 0.7rem;">LATEST AND GREATEST</div>
      <div class="latest-journals">
        <h3 class="journal-title">Gridsome with Forestry CMS</h3>
        <h3 class="journal-title">VueJS for your next project</h3>
        <h3 class="journal-title">macOS development environment</h3>
        <h3 class="journal-title">About Typography</h3>
      </div>
    </div>
    <footer class="footer" style="margin-bottom:200px;font-size:0.9rem;margin-top:100px">Copyright &copy; 2021</footer>
  </div>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!',
  },
}
</script>

<style>
.content {
  display: flex;
  flex-flow: column;
  justify-content: start;
  align-items: center;
}
header {
  width: 60%;
  position: fixed;
  display: flex;
  flex-flow: row;
  justify-content: space-between;
  align-items: center;
  margin-top: 30px;

  font-weight: 700;
}
.container {
  width: 60%;
  margin-top: 150px;
}
.hero {
  display: flex;
  flex-flow: column;
  justify-content: center;
  align-items: center;

  margin: 20px;
}
.hero-subtitle {
  width: 50%;
  text-align: center;
}
.projects {
  width: 100%;
  display: flex;
  flex-flow: column;
  justify-content: start;
  align-items: center;
  margin-top: 120px;
}
.projects2 {
  width: 100%;
  display: flex;
  flex-flow: row;
  justify-content: space-between;
  align-items: center;
}
.project {
  height: 100%;
  display: flex;
  flex-flow: column;
  justify-content: space-between;
  align-items: center;
  margin-top: 20px;
  margin-bottom: 20px;
}
.project1,
.project4 {
  width: 100%;
}
.project2,
.project3 {
  width: 46%;
}
.pic {
  width: 100%;
  transition: all .2s linear 0s;
}
.pic:hover {
    transform: scale(1.05, 1.05);
}
.pic2,
.pic3 {
  height: 580px;
  object-fit: cover;
}
.category {
  font-size: 0.7rem;
}
.latest-journals {
  width: 100%;
  display: flex;
  flex-flow: row;
  justify-content: center;
  align-items: center;
}
.journal-title{
  padding: 50px;
  transition: all .2s linear 0s;
}
.journal-title:hover {
    background-color: #DBDBDB;
}
footer {
  width: 60%;
}
</style>
