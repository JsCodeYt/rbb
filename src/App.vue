<template>
  <div class="app">
    <Navbar />
    <Header />
    <Portfolio />
    <Social />
    <TTS />
    <Plane />
    <People />
  </div>
  <Footer />
</template>
<script>
import Navbar from './components/Navbar.vue';
import Header from "./components/Header.vue"
import Portfolio from './components/Portfolio.vue';
import Social from './components/Social.vue';
import TTS from "./components/TTS.vue"
import Plane from "./components/Plane.vue"
import People from "./components/People.vue";
import Footer from "./components/Footer.vue"
import Aos from "aos"
import "aos/dist/aos.css"

export default {
  components: {
    Navbar,
    Header,
    Portfolio,
    Social,
    TTS,
    Plane,
    People,
    Footer
  },
  created() {
    Aos.init()
  }
}
</script>
<style>
.app {
  padding: 10px 200px;
}
</style>