<template>
  <div class="root">
    <div class="slideshow">
      <ul class='slide'>
        <li class="slide__item">
          <img class="slide__img" src="../assets/pic_2.jpg" />
          <span class="slide__text" style="font-size:160px;">Kitchen Cabinet</span>
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
   <img class="liner" src="../assets/liner.jpg">
  </div>
</template>

<script>
export default {
  name: 'template',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import 'https://fonts.googleapis.com/css?family=Amatic+SC:700';


.slide {
  margin: 0;
  padding: 0;
  list-style: none;
}

.slide__img {
  width: 100%;
  height: 600px;
  object-fit: cover;
  display: block;
  opacity: 0.7; 
 }


.slide__item {
  position: relative;
  background-color: #000000;
}

.slide__text {
  position: absolute;
  top: 50%;
  left: 50%;
  font-family: 'Amatic SC', cursive; 
  color: #ffffff;
  transform: translate(-50%, -50%);
  display: flex;
  border-width: 6px;
  border-style: solid;
  border-color: #ffffff;
  padding: 50px;
}

.liner {
  display: block; 
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
  font-weight: regular; 
  color: #ffffff;
  font-size: 22px;
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
