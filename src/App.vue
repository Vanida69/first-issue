<template>
  <div id="app">
    <v-header />
    <router-view></router-view>
  </div>
</template>

<script>
import VHeader from './components/Header';

export default {
  name: 'app',
  components: {
    VHeader,
  },
}
</script>

<style>
@import '../node_modules/normalize.css';

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
