<template>
  <div id="app">
    <v-header />
    <router-view></router-view>
    <v-footer />
  </div>
</template>

<script>
import VHeader from './components/Header';
import VFooter from './components/Footer';

export default {
  name: 'app',
  components: {
    VHeader,
    VFooter,
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

.material-design-icon {
  display: inline-flex;
  align-self: center;
  position: relative;
  height: 1em;
  width: 1em;
}

.material-design-icon__svg {
  display: inline-flex;
  align-self: center;
  fill: currentColor;
  position: absolute;
  bottom: -0.125em;
  height: 1em;
  width: 1em;
}
</style>
