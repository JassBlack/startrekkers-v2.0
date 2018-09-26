<template>
  <div id="app">
    <headerNavigation></headerNavigation>
    <main class="container">
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
import Home from './views/Home.vue'
import MusicShare from './views/MusicShare.vue'
import HeaderNavigation from './components/HeaderNavigation.vue'

export default {
  name: 'App',
  components: {
    HeaderNavigation,
    Home,
    MusicShare
  }
}
</script>

<style>

@import './assets/css/normalize.css';

@font-face {
  font-family: 'OpenSans';
  src: url('./assets/fonts/opensans.woff2') format('woff2'),
        url('./assets/fonts/opensans.woff') format('woff');
  font-weight: 400;
  font-style: normal;
}

@font-face {
  font-family: 'OpenSans';
  src: url('./assets/fonts/opensansbold.woff2') format('woff2'),
        url('./assets/fonts/opensansbold.woff') format('woff');
  font-weight: 700;
  font-style: normal;
}

@font-face {
  font-family: 'OpenSans';
  src: url('./assets/fonts/opensanslight.woff2') format('woff2'),
        url('./assets/fonts/opensanslight.woff') format('woff');
  font-weight: 300;
  font-style: normal;
}

#app {
  font-family: 'OpenSans', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  position: relative;
}

#app:after {
  content: "";
  position: fixed;
  top: 0;
  height: 100vh;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: -1;
  background: url("./assets/images/background.jpg") center center;
  background-size: cover;
  background-repeat: no-repeat;
}

.container {
  padding: 0 8%;
}

</style>
