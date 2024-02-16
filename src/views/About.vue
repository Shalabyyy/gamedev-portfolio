<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Youssef Shalaby</strong>, a Game and Software Developer with 4+ years of experience<br/>
        I am also a gamer and I I love discussing, designing and developing apps and games in general. 
      </div>

      <div style="margin-top: 20px;">I've worked on  <router-link to="/game-projects">alot of games</router-link> (either to release them, to showcase my capabilities using Unity, or just to play around), 
        on. I also worked on a couple of non-game <router-link to="/other-projects">projects</router-link>, and took part in <router-link to="/resume">a few things</router-link> as well.</div>

      <div style="margin-top: 40px;">I'm I'm currently working as a Unity Developer at <strong>Digitalpen</strong>. You can reach me at <a href="mailto:youshalaby@gmail.com">youshalaby@gmail.com</a> or <router-link to="/contact">through here</router-link> for any opportunities or inquiries.</div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of John" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>