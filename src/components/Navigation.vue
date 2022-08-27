<script setup>
// import { RouterLink, RouterView } from 'vue-router'
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="nav_bar">
<RouterLink class="logo" to="/">Greach</RouterLink>
<div >
    <RouterLink to="#">How it works</RouterLink>
    <RouterLink class="middle_links" to="#">Download</RouterLink>
    <RouterLink to="#">Conatct Us</RouterLink>
</div>
<button class="nav_button">Register</button>
  </div>
</template>

<style scoped>
.nav_bar {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
   width: 100%;
   padding: 20px 40px;
  gap: 275px;
  background: #ffffff05;
  backdrop-filter: blur(10px);
    position: -webkit-sticky; /* Safari */
  position: sticky;
  top: 0;
  z-index: 99;
}
.middle_links{
   margin:0 30px
}
a{
    font-weight: 500;
    color: #000000;
}
.nav_button {
    background-color: #000000;
    color: #ffffff;
    padding: 1em 3.5em;
    border-radius: 5px;
}
.logo {
    font-size: 24px;
    font-weight: 700;
    color: #0FAC11;
}
</style>
