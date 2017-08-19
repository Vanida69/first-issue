<template>
  <div class="root">
    <div class="slideshow">
      <ul class='slide'>
        <li class="slide__item">
          <img class="slide__img" src="../assets/pic_2.jpg" />
          <span class="slide__text">Kitchen Cabinet</span>
        </li>
       </ul>
      </div>
   <div class="primary-menu">
      <ul class="menu">
        <li class="menu__item">
          <router-link class="menu__link" to="/">Home</router-link>
        </li>
        <li class="menu__item">
          <router-link class="menu__link" to="/about">About Us</router-link>
        </li>
        <li class="menu__item">
          <router-link class="menu__link" to="/pages">Pages</router-link>
        </li>
        <li class="menu__item">
          <router-link class="menu__link" to="/addons">Addons</router-link>
        </li>
        <li class="menu__item">
          <router-link class="menu__link" to="/blog">Blog</router-link>
        </li>
        <li class="menu__item">
          <router-link class="menu__link" to="/portfolio">Portfolio</router-link>
        </li>
        <li class="menu__item">
          <router-link class="menu__link" to="/contact">Contact</router-link>
        </li>
      </ul> 
   </div> 
  </div>
</template>

<script>
export default {
  name: 'template',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.slide {
  width: 100%;
  height: 600px;
  object-fit: cover;
}

.primary-menu {
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
}

.root {
  position: relative;
}

.menu {
  list-style: none;
  display: flex;
  justify-content: center;
  padding: 0; 
}

.menu__item {
  font-weight: bold; 
  color: #ffffff;
  margin: 1em;
}

.menu__link {
  color: #ffffff; 
  text-decoration: none;
}

.menu__link:hover {
  color: #CC0000;
  
}

</style>
