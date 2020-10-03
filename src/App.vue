<template>
  <Navbar />
  <Hero />
  <Features />
  <Testimonals />
  <call-to-action></call-to-action>
  <footer></footer>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import CallToAction from "./components/CallToAction.vue";
import Features from "./components/Features.vue";
import Hero from "./components/Hero.vue";
import Testimonals from "./components/Testimonals.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    Navbar,
    CallToAction,
    Features,
    Hero,
    Testimonals,
    Footer,
  },
};
</script>
