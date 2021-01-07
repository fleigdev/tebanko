<template>
  <div id="app">
    <Navbar />
    <LandingPage />

    <Footer />
  </div>
</template>

<script>
import Footer from './components/Footer.vue';
import Navbar from './components/Navbar.vue';
import LandingPage from './views/LandingPage.vue';

export default {
  name: 'App',
  components: {
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

  color: #2c3e50;
}
</style>
