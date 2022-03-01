<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import DownContainer from "./components/DownContainer.vue";
import UpContainer from "./components/UpContainer.vue";
</script>

<template>
  <div>
    <UpContainer/>
    <DownContainer/>
  </div>
</template>

<style lang="scss">
*{
	box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
