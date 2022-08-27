<template >
    <div class="hero_container">
        <div class="left_hero_text">
                <p class="smallbtn">GREACH A RIDE</p>
                <p class="hero_text">Find the <span>best </span> <br> Taxi <span>ride</span> for <br> you</p>
            <p class="hero_subtext">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ac dignissim maurisonsectetur adipiscing elit. Ac dignissim maurisonsectetur adipiscing elit. Ac dignissim mauris pellentesque vitae. Dui lacus et dui euismod interdum ut. At </p>
            <div class="button_div">
                <button class="primary_button">Download</button>
                <button class="secondary_button">Join Waitlist</button>
            </div>
        <div class="hero_stats">
            <div>
                <p class="hero_stats_header">500</p>
                <p>Drivers and Riders Available</p>
            </div>
            <div>
                <p class="hero_stats_header">99%</p>
                <p>Fast and Reliable</p>
            </div>
        </div>
   
        </div>
        <div>
            <img alt="Hero Img" class="logo" src="@/assets/hero_img.png"/>
        </div>
    </div>
</template>
<script setup>
</script>
<style scoped>
.hero_stats {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: flex-start;
    width: 70%;
   
}
.left_hero_text {
     display: flex;
     flex-direction: column;
     justify-content: baseline;
     gap: 10px;

}
    .smallbtn {
        font-size: 12px;
        color: #ffffff;
        background-color: #0FAC11;
        border-radius: 4px;
        padding: 10px;
        font-weight: 600;
        width: 30%;
        text-align: center;
    }
    .hero_text {
        font-size: 60px;
        color: #000000;
        font-weight: 900;
        /* width: 80%; */
        line-height: 70px;
        letter-spacing: 5px;
    }
    span{
        color: #0FAC11;
        font-size: 60px;
        font-weight: 700;
    }
    .hero_subtext{
        width: 75%;
font-size: 16px;
line-height: 36px;
color: #404040;
    }
    .hero_container{
        display: flex;
        justify-content: space-between;
        width: 90%;
        margin: 0 auto;
  background-image: url("@/assets/BG.svg");
       
    }
   
    .button_div{
        width: 80%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin-top: 30px;
    }
   
    .primary_button {
        background-color: #0FAC11;
        border: none;
        color: #ffffff;
        font-weight: 700;
        padding: 1.3em 4.5em;
        border-radius: 5px;
    }
     .primary_button:hover{
        background-color: #056406;
        transition: 0.3s;
        cursor: pointer;
    }
    .secondary_button {
        background-color: transparent;
        border: none;
        color: #000000;
        font-weight: 700;
        padding: 1.3em 3.5em;
        border-radius: 5px;
        border: 1px dashed #000000;
    }
    .secondary_button:hover{
        background-color: #000000;
        color: #ffffff;
        cursor: pointer;
        transition: 0.3s;
    }
    .hero_stats_header {
        font-weight: 800;
        font-size: 32px;
        line-height: 48px;
        letter-spacing: 1px;
    }
    /*  */
    @media screen and (max-width: 1080px) {
     .hero_container{
        display: block;
        text-align: center;
        width: 80%;
        margin: 0 auto;
  background-image: url("@/assets/BG.svg");
  }
   .hero_subtext{
        width: 100%;
        font-size: 16px;
        line-height: 36px;
        color: #404040;
        margin-top: 10px;
    }
     .smallbtn {
        font-size: 12px;
        color: #ffffff;
        background-color: #0FAC11;
        border-radius: 4px;
        padding: 10px;
        font-weight: 600;
        width: 30%;
        margin: 20px auto 0;
        text-align: center;
    }
      .button_div{
        width: 80%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin: 20px auto;
    }
    .hero_stats {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: flex-start;
    width: 70%;
    margin: 0 auto 30px;
   
}
}
</style>