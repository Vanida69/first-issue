<template>
  <div class="root">
    <div class="flex">
      <div class="box">
        A1
      </div>
      <div class="box">
        A2
      </div>
    </div>
    <div>
      B
    </div>
    <div class="flex">
      <div class="box">
        C1
      </div>
      <div class="box">
        C2
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home-port',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.flex {
  display: flex;
  justify-content: space-between;
}

.box {
  flex: 1 1 auto;
}

</style>
