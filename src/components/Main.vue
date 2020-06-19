<template>
  <main>
    <div class="project" :style="{ backgroundImage: `url(${backgroundUrl})` }"></div>
    <div class="project" :style="{ backgroundImage: `url(${backgroundUrl})` }"></div>
    <div class="project" :style="{ backgroundImage: `url(${backgroundUrl})` }"></div>
    <div class="project" :style="{ backgroundImage: `url(${backgroundUrl})` }"></div>
    <div class="project" :style="{ backgroundImage: `url(${backgroundUrl})` }"></div>
    <div class="project" :style="{ backgroundImage: `url(${backgroundUrl})` }"></div>
  </main>
</template>

<script>
import backgroundUrl from "../assets/demo.jpg";

export default {
  name: "Main",
  data() {
    return {
      backgroundUrl
    };
  }
};
</script>

<style scoped>
main {
  display: grid;
  grid-gap: 10px;
  /* Space between items */
  grid-template-columns: 1fr 1fr 1fr;
  /* Decide the number of columns and size */
  max-height: calc(100vh - 200px);
  overflow-y: scroll;
}

.project {
  height: 300px;
  background-position: center; /* Center the image */
  background-repeat: no-repeat; /* Do not repeat the image */
  background-size: cover;
}
</style>