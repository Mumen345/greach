<template >
    <div class="hero_container">
        <div class="left_hero_text">
                <p class="smallbtn">Greach a Ride with a Trusted</p>
                <P class="second_text">Community of</P>
                <P class="third_text"><span>Friends</span>  and </P>
                <p class="forth_text"><span>Professionals</span></p>
                <p class="fifth_text"><span>on the go...</span></p>
            <p class="hero_subtext">Greach a Ride with a Trusted Community of Friends and Working Professionals</p>
            <div class="button_div">
                <button class="primary_button">Download App</button>
                <button class="secondary_button">Join Waitlist</button>
            </div>
        <div class="hero_stats">
            <div>
                <p class="hero_stats_header">500+</p>
                <p>Drivers and Riders <br> Available</p>
            </div>
            <div>
                <p class="hero_stats_header">99%</p>
                <p>Secure and <br> Affordable</p>
            </div>
        </div>
   
        </div>
        <div class="web">
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
    gap: 32%;
    color: #ffffff;
    /* width: 70%; */
   
}
.second_text {
    font-style: normal;
font-weight: 800;
font-size: 36px;
line-height: 54px;
letter-spacing: 6px;
color: #FFFFFF;
}
.fifth_text {
    font-weight: 800;
font-size: 55.2632px;
line-height: 83px;
letter-spacing: 5.52632px;
color: #ffffff;
}
.forth_text{
    font-style: normal;
font-weight: 800;
font-size: 55.2632px;
line-height: 83px;
letter-spacing: 5.52632px;
}
.left_hero_text {
     display: flex;
     flex-direction: column;
     justify-content: baseline;
     gap: 10px;

}
.third_text {
    font-weight: 800;
    font-size: 55.26px;
    line-height: 83px;
    letter-spacing: 5.52632px;
    color: #ffffff;
}
    .smallbtn {
        width: 439px;
        height: 24px;
        font-style: normal;
        font-weight: 600;
        font-size: 16px;
        color: #2AAA0B;
    }
    .hero_text {
        font-size: 60px;
        color: #ffffff !important;
        font-weight: 900;
        /* width: 80%; */
        line-height: 70px;
        letter-spacing: 5px;
    }
    span{
        color: #0FAC11;
       font-weight: inherit !important;
       font-size: inherit !important;
    }
    .hero_subtext{
        width: 75%;
        font-size: 16px;
        line-height: 36px;
        color: #ffffff;
    }
    .hero_container{
        display: flex;
        justify-content: space-around;
        width: 90%;
        margin: 9% auto 0;
        /* background-image: url("@/assets/BG.svg"); */
       
    }
   
    .button_div{
        width: 100%;
        display: flex;
        gap: 20%;
        margin-top: 30px;
    }
   
    .primary_button {
        background-color: #0FAC11;
        border: none;
        color: #ffffff;
        font-weight: 700;
        padding: 1.3em 3.5em;
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
        color: #ffffff;
        font-weight: 700;
        padding: 1.3em 3.5em;
        border-radius: 5px;
        border: 1px dashed #ffffff;
    }
    .secondary_button:hover{
        background-color: #00000000;
        color: #ffffff;
        cursor: pointer;
        transition: 0.3s;
    }
    .hero_stats_header {
        font-weight: 800;
        font-size: 32px;
        line-height: 48px;
        letter-spacing: 1px;
        color: #ffffff;
    }
    /*  */
    @media screen and (max-width: 1080px) {
    .web{
      display: none;
    }
     .hero_container{
        display: flex;
        text-align: center;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        width: 90%;
        margin: 70px auto -20px;
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
    gap: 30%;
    width: 90%;
    margin: 0 auto 60px;
   
}
}
</style>