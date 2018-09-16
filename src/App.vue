<template>
  <div id="app">
    <navigation></navigation>
    <h1>kekekekek</h1>
    <router-view></router-view>
  </div>
</template>

<script>
import Home from './views/Home.vue'
import MusicShare from './views/MusicShare.vue'
import Navigation from './components/Navigation.vue'

export default {
  name: 'App',
  components: {
    Navigation,
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
  text-align: center;
  color: #2c3e50;
}

.body {
  
}

</style>
