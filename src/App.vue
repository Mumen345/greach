<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
import Navigation from './components/Navigation.vue' 
import Howitworks from './components/Howitworks.vue' 
import DownloadSection from './components/DownloadSection.vue' 
import Waitlist from './components/Waitlist.vue' 
// import Newsletter from './components/Newsletter.vue' 
import Hero from './components/Hero.vue'
import FooterSection from './components/FooterSection.vue' 
</script>

<template>
<div class="headersection">
  <Navigation />
  <Hero />
</div>
  <Howitworks />
  <DownloadSection />
  <Waitlist />
  <!-- <Newsletter /> -->
  <FooterSection />
    
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
    width: 100%;
    height: 100%;
    padding-bottom: 70px;
    background-repeat: repeat;
    background-size: cover;

 }
</style>
