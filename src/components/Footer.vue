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
              twitter
            </a>
          </li>
          <li>
            <a class="menu__icon" href="http://plus.google.com">
              gplus
            </a>
          </li>
          <li>
            <a class="menu__icon" href="http://facebook.com">
              facebook
            </a>
          </li>
          <li>
            <a class="menu__icon" href="http://youtube.com">
              youtube
            </a>
          </li>
        </ul>
      </div>

      <div class="footer__item">
        <h4 class="header">Subsrcibe Us</h4>
        <div class="caption">
          This sounded a very good reason and alike wes quite pleased to konw it. I never thought.
        </div>
        <input type="text" class="Subsrcibe__email" placeholder="E-Mail" />
        <div class="subsrcibe__button">
          <button class="Subsrcibe__sub">Subsrcibe</button>
        </div>
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
export default {
  name: 'footer',
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
  width: 30%;
  margin: 0 2%;
}

.footer__item:first-child,
.footer__item:last-child {
  width: 30%;
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
  padding: 0;
  display: block;
}

.caption {
  margin: 0;
}
</style>
