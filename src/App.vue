<template>
  <div id="app">
    <!-- <vheader></vheader> -->
    <div class="tab"></div>
    <div class="content"></div>
    <router-view/>
  </div>
</template>

<script>
import vheader from './components/header/header.vue'
export default {
  components: {
    vheader
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
