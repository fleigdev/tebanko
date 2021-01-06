<template>
  <div id="app">
    <Navbar />
    <LandingPage />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Bienvenidos a TeBanko" />
    <img src="./assets/img/logo-light.png" class="l-light" height="24" alt="" />
    <img
      src="./assets/img/logo-tebanko.png"
      class="l-light"
      height="24"
      alt=""
    />
    <Footer />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Footer from './components/Footer.vue';
import Navbar from './components/Navbar.vue';
import LandingPage from './views/LandingPage.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Footer,
    Navbar,
    LandingPage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
