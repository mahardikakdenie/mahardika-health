<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
// import HelloWorld from "./components/HelloWorld.vue";
import Navbar from './components/Navbar.vue';
import Banner from './components/Banner.vue';
import Summary from './components/Summary.vue';
import BestService from './components/BestService.vue';
import consulting from './components/Consulting.vue'
</script>

<template>
  <div class="">
    <Navbar />
    <Banner />
    <Summary />
    <BestService />
    <consulting />
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
  background-color: #FDF4EF}
</style>
