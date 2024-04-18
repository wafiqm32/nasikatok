<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
<div class="small-big">
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="./assets/logo.jpg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/logo.jpg" class="logo vue" alt="Vue logo" />
      <h1>Hello my name is Wafiq, my student id is 22ftt1516</h1>
      <h2>SIUUUUUUUUUUUUUUUUUUUU</h2>
      <h3>information</h3>
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>