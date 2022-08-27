<template >
    <div class="hero_container">
        <div>
            
            <p class="smallbtn">GREACH A RIDE</p>
            <p class="hero_text">Find the <span>best</span>  
    Taxi <span>ride</span> for you</p>
    <p class="hero_subtext">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ac dignissim mauris pellentesque vitae. Dui lacus et dui euismod interdum ut. At </p>
        </div>
        <div>
            <img alt="Hero Img" class="logo" src="@/assets/hero_img.png"/>
        </div>
    </div>
</template>
<script setup>
</script>
<style scoped>
    .smallbtn {
        font-size: 12px;
        color: #ffffff;
        background-color: #0FAC11;
        border-radius: 4px;
        padding: 10px;
        font-weight: 600;
        width: 20%;
    }
    .hero_text {
        font-size: 60px;
        color: #404040;
        font-weight: 700;
        width: 70%;
    }
    span{
        color: #0FAC11;
        font-size: 60px;
        font-weight: 700;
    }
    .hero_subtext{
        /* width: 30%; */
font-size: 16px;
line-height: 36px;
color: #404040;
    }
    .hero_container{
        display: flex;
        justify-content: space-evenly;
        align-items: flex-start;
        height: 100vh;
       
    }
</style>