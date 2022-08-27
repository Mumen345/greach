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
    <RouterLink to="/">How it works</RouterLink>
    <RouterLink class="middle_links" to="/about">Download</RouterLink>
    <RouterLink to="/about">Conatct Us</RouterLink>
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
   width: 90%;
   max-width: 1550px;
   margin: 20px auto;
gap: 275px;
background: rgba(255, 255, 255, 0.08);
backdrop-filter: blur(14px);
    position: -webkit-sticky; /* Safari */
  position: sticky;
  top: 0;
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
