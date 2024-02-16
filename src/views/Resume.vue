<template>
  <div>
    <h1>Resume</h1>

    <div class="paragraph">
      I'm <strong>Youssef Shalaby</strong>, Dedicated and Passionate game developer and software engineer, with an eye to detail on design, aesthetic and game mechanics. I am always looking to improve myself by working on different types of games and utilizing my set of technical skills and  methodology of problem solving to produce innovative and creative games.
       <router-link to="/contact">contact me for any inquiries</router-link>.
      <br />
      <br>
      
      <div style="margin-top:20px; margin-bottom:20px;">
        <a class="download-link" href="https://docs.google.com/document/d/1ANlwbduWokz8hqvjoce3eMoNW43Hz7vc/edit?usp=sharing&ouid=101844051890393184045&rtpof=true&sd=true" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> View Resume 🇬🇧</a>
        <div style="clear:both"></div>
      </div>
    </div>
    <div class="full-content">
      <div style="clear:both" />   
      <SkillRate name="Enthusiasm" :rate="0" />   
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SkillRate from "@/components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  components: {
    SkillRate,
  },
});
</script>

<style scoped>
h2 {
  font-weight: 100;
  font-size: 2em;
  margin: 0px;
  padding: 0px;
  padding-top: 50px;
}
h3 {
  font-weight: 100;
  font-size: 1.6em;
  margin: 0px;
  padding: 0px;
  padding-top: 30px;
}
h4 {
  font-weight: 100;
  font-size: 1.3em;
  margin: 0px;
  padding: 0px;
  padding-top: 15px;
  font-style: italic;
}

.paragraph {
  max-width: 700px;
}

.download-link {
  float:left;
  margin-right: 50px;
}

.full-content div {
  max-width: 800px;
}

.skill-set h3 {
  padding-bottom: 10px;
}

.photo img {
  height: 300px;
  width: 300px;
}

.tech-stack {
  font-style: italic;
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
    padding: 30px;
    padding-left: 80px;
  }

  .skill-set {
    float: left;
    padding-right: 60px; 
  }
}
</style>