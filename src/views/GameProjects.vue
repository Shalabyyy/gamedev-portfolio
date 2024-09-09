<template>
  <div>
    <h1>My Game Portfolio</h1>

    <div style="margin-bottom: 10px;">
      The following are some projects I designed, sketched or wrote. My personal favourite is Void Seeker
    </div>
    <ProjectsList v-bind:projects="projects" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import ProjectsList from "@/components/ProjectsList.vue";
import gameProjectsData from "@/data/GameProjectsData.ts";

export default Vue.extend({
  name: "GameProjects",
  components: {
    ProjectsList,
  },
  data: function () {
    return {
      projects: gameProjectsData,
    };
  },
});
</script>
