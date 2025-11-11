<template>
  <div class="app">
    <Squares 
      direction="diagonal"
      :speed="1"
      :squareSize="40"
      borderColor="#999"
      hoverFillColor="#222"
    />
  </div>
</template>

<script setup lang="ts">
  import Squares from "./components/squares.vue";
</script>
<style>
* {
  margin: 0 !important;
}
.app {
  width: 100vw;
  height: 100vh;
  padding: 0;
}
</style>
