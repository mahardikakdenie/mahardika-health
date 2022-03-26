<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
// import HelloWorld from "./components/HelloWorld.vue";
import Navbar from "./components/Navbar.vue";
import Banner from "./components/Banner.vue";
import Summary from "./components/Summary.vue";
import BestService from "./components/BestService.vue";
import consulting from "./components/Consulting.vue";
import LookingFor from "./components/LookingFor.vue";
import Docters from "./components/Docters.vue";
import EasyStep from "./components/EasyStep.vue";
import bestDoctor from "./components/BestDoctor.vue";
import healthcare from "./components/AppHealth.vue";
import FooterHealth from "./components/FooterHealth.vue";
</script>

<template>
  <div class="">
    <Navbar />
    <Banner />
    <Summary />
    <BestService />
    <consulting />
    <looking-for />
    <docters />
    <easy-step />
    <br />
    <best-doctor />
    <healthcare />
    <FooterHealth />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
* {
  background-color: #fdf4ef;
}
</style>
