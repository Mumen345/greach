<script setup>
import Navigation from '@/components/Navigation.vue'
import Howitworks from '@/components/Howitworks.vue' 
import DownloadSection from '@/components/DownloadSection.vue' 
import Waitlist from '@/components/Waitlist.vue' 
// import Newsletter from './components/Newsletter.vue' 
import Ambassador from '@/components/Ambassador.vue' 
import Hero from '@/components/Hero.vue'
import Faq from '@/components/Faq.vue' 
import FooterSection from '@/components/FooterSection.vue' 

</script>

<template>
<div class="headersection">
  <Navigation />
  <Hero />  
</div>
  <Howitworks />
    <DownloadSection />
    <Waitlist />
    <Faq />
    <Ambassador />
    <FooterSection />
  <RouterView />
</template>
<style>
   .headersection{
    background-image: url("@/assets/BG.svg");
    width: 100% !important;
    height: 100%;
    /* padding-bottom: 70px; */
    background-repeat: repeat;
    background-size: cover;
 }
</style>