<template>
  <div class="root">
    <div class="main-feature">
      <div class="feature__item">
        <img class="feature__icon" src="../assets/icon-2.svg" />
        <h4 class="feature__caption">
          Includes carefully crafted pre-built page Floox
        </h4>
        <div class="feature__desc">
          Layouts for your next project.
        </div>
      </div>
    </div>

    <div class="feature">
      <div class="feature__item">
        <img class="feature__icon" src="../assets/icon-3.svg" />
        <h4 class="feature__caption">
          Brand Strategy
        </h4>
        <div class="feature__desc">
          Dummy text of the printing and typesetting industry
        </div>
      </div>
      <div class="feature__item">
        <img class="feature__icon" src="../assets/icon-4.svg" />
        <h4 class="feature__caption">
          Creative Design
        </h4>
        <div class="feature__desc">
          Dummy text of the printing and typesetting industry
        </div>
      </div>
      <div class="feature__item">
        <img class="feature__icon" src="../assets/icon-5.svg" />
        <h4 class="feature__caption">
          Clean Structure
        </h4>
        <div class="feature__desc">
          Dummy text of the printing and typesetting industry
        </div>
      </div>
    </div>
  </div>
</template>

<script>


export default {
  name: 'features',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.root {
  position: relative;
  font-weight: ragular;
  color: #ffffff;
  background-color: #232323;
  margin: 0 auto;
  text-align: center;
}

.main-feature {
  color: #ffffff;
  font-size: 1.1em;
  margin: 0 auto;
  line-height: 0;
  padding: 1.5em 2.5em;
}

.feature {
  display: flex;
  justify-content: space-between;
  padding: 0.5em 20em;
}

.feature__item {
  justify-content: space-between;
  color: #ffffff;
  font-size: 1.2em;
  margin: 0;
  line-height: 1.2em;
  padding: 1.5em 5em;
}

.feature__icon {
  justify-content: space-between;
}

.feature__caption {}

.feature {}
</style>
