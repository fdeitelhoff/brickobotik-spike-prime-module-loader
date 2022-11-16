<script setup lang="ts">
import SpikePrime from './components/SpikePrime.vue';
</script>

<template>
  <div>
    <a href="https://www.brickobotik.de" target="_blank">
      <img
        class="logo"
        src="https://www.brickobotik.de/wp-content/uploads/2021/05/Logo_4-Farben_Wortmarke_Horizontal_2.png"
      />
    </a>
  </div>
  <SpikePrime />
</template>

<style scoped>
.logo {
  height: 5em;
  padding: 1.5em;
  will-change: filter;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #fece00);
}
</style>
