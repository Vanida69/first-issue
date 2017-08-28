<template>
  <div class="root">
    <div class="footer">
      <div class="footer__item">
        <h4 class="header">Siam house &amp; Home Co., Ltd</h4>
        <div class="caption">
          Lorem Ipsum is simply dummy text of the printing and typesetting industry
        </div>
        <table class="address">
          <tbody>
            <tr>
              <td>A</td>
              <td>2659-2667 Ladprao rd., Klogjaokunsingha, Wangthonglang BKK 10310</td>
            </tr>
            <tr>
              <td>E</td>
              <td>info@siamhouse.co.th</td>
            </tr>
            <tr>
              <td>T</td>
              <td>+66 0 2542 1920</td>
            </tr>
          </tbody>
        </table>
      </div>

      <div class="footer__item">
        <h4 class="header">Quick link</h4>
        <ul class="menu">
          <li>
            <router-link class="menu__link" to="/about">About Us</router-link>
          </li>
          <li>
            <router-link class="menu__link" to="/team">Our Team</router-link>
          </li>
          <li>
            <router-link class="menu__link" to="/service">Service</router-link>
          </li>
          <li>
            <router-link class="menu__link" to="/project">Project</router-link>
          </li>
          <li>
            <router-link class="menu__link" to="/blog">Blog</router-link>
          </li>
          <li>
            <router-link class="menu__link" to="/contact">Contact Us</router-link>
          </li>
        </ul>
      </div>

      <div class="footer__item">
        <h4 class="header">Support</h4>
        <ul class="menu">
          <li>
            <router-link class="menu__link" to="/job">Jobs</router-link>
          </li>
          <li>
            <router-link class="menu__link" to="/privacy">Privacy Policy</router-link>
          </li>
        </ul>

        <h4 class="header">Follow Us</h4>
        <ul class="menu icon-menu">
          <li>
            <a class="menu__icon" href="http://twitter.com">
              <twitter></twitter>
            </a>
          </li>
          <li>
            <a class="menu__icon" href="http://plus.google.com">
              <google></google>
            </a>
          </li>
          <li>
            <a class="menu__icon" href="http://facebook.com">
              <facebook></facebook>
            </a>
          </li>
          <li>
            <a class="menu__icon" href="http://youtube.com">
              <youtube></youtube>
            </a>
          </li>
        </ul>
      </div>

      <div class="footer__item">
        <h4 class="header">Subsrcibe Us</h4>
        <div class="caption">
          This sounded a very good reason and alike wes quite pleased to konw it. I never thought.
        </div>
        <input type="text" class="subscribe__email" placeholder="your@email.com" />
        <button class="subscribe__sub">Subscribe</button>
        </div>
    </div>

    <div class="credit">
      <div>
        Copyright &copy; 2017 siamhouse.
      </div>
      <div>
        Design &amp; Development By siamhouse.
      </div>
    </div>
  </div>
</template>

<script>
 
import Twitter from 'icons/twitter'; 
import Google from 'icons/google-plus';
import Facebook from 'icons/facebook';
import Youtube from 'icons/youtube-play';

export default {
  name: 'footer',

  components: { 
    Twitter,
    Google,
    Facebook,
    Youtube
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
  display: flex;
  justify-content: space-between;
  margin: 2em 0 0;
}

.footer__item {
  width: 25%;
  margin: 0 2%;
}

.footer__item:first-child,
.footer__item:last-child {
  width: 25%;
}

.root {
  position: relative;
  font-weight: ragular;
  color: #ffffff;
  font-size: 15px;
  margin: 0;
  background-color: #232323;
}

.header {
  font-weight: ragular;
  color: #ffffff;
  font-size: 18px;
  text-transform: uppercase;
}

.menu {
  list-style: none;
  margin: 0;
  padding: 0;
}

.menu__link {
  color: #ffffff;
  text-decoration: none;
  padding: 0.8em 0;
  display: block;
}

.caption {
  margin: 0 0 1em 0; 
  line-height: 1.7; 
}

.address {
  line-height: 2.5;
}

.address td:first-child {
  color: #cf2020;
  vertical-align: top;
  font-weight: bold;
  font-size: 20px;
  width : 2em;
}

.address tr {
  margin: 0; 
}

.subscribe__email {
  border: 1px solid #ccc;
  display: block;
  line-height: 1;
  box-sizing: border-box;
  width: 100%;
  padding: .4em;
}

.subscribe__sub{
  display: block;
  cursor: pointer;
  padding: 0.5em 1.5em;
  margin: 1em 0 .75em auto; 
  background-color: #ff0000;
  color: #ffffff;
  font-weight: bold;
  font-size: 14px;
  border-width: 0;
  border-style: solid;
  border-color: none;
  text-transform: uppercase;
}

.credit {
  display: flex;
  justify-content: space-between;
  margin:  2%;
  padding: 2em 0;
  border-top-width: 1px;
  border-top-style: solid;
  border-top-color: #ffffff;

}

 .icon-menu {
   display: flex;
}

 .menu__icon {
   display: block;
   cursor: pointer;
   padding: .25em .35em;
   margin: 0 0.3em; 
   background-color: #ff0000;
   color: #ffffff;
   font-size: 2.1em;
   border-width: 0;
   border-style: solid;
   border-color: none;
   border-radius: 50%;
   text-transform: uppercase;
}


</style>
