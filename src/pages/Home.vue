<template>
  <div class="root">
    <v-features />
    <v-home-port />
  </div>
</template>

<script>
import VFeatures from '../components/Features'
import VHomePort from '../components/HomePort'

export default {
  name: 'home',
  components: {
    VFeatures, 
    VHomePort
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
