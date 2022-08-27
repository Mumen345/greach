<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
import Navigation from './components/Navigation.vue' 
import Howitworks from './components/Howitworks.vue' 
import Hero from './components/Hero.vue'
</script>

<template>
<div class="headersection">

  <Navigation />
  <Hero />
</div>
  <Howitworks />
    
    <!-- <HelloWorld /> -->
  <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header> -->

  <RouterView />
</template>

<style scoped>
 .headersection{
    background-image: url("@/assets/BG.svg");

 }
</style>
