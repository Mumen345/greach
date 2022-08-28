<template>
    <div class="download_section_container">
        <div class="move_down">
            <p class="section_text"><span>Download</span>  our <span>App</span> </p>
            <div class="download_link">
             <a href="#"><img alt="apple logo" src="@/assets/appstore.svg"/></a>
             <a href="#"><img alt="play store logo" src="@/assets/googleplay.svg"/></a>
            </div>
            <div class="section_CTA">
                <button class="primary_button">Signup as a Driver</button>
                <button class="secondary_button">Signup as a Driver</button>
            </div>
       </div>
        <div class="move_down"><img alt="phone mockup" class="" src="@/assets/Mockups.svg"/></div>
    </div>
</template>
<script setup>
</script>
<style scoped>
    .download_section_container p{
        text-align: center;
    }
    .download_section_container {
        background-image: url("@/assets/download_bg.png");
        background-repeat: no-repeat;
        background-size: auto;
        height: 340px;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: flex-start;
    }
     span{
        color: #0FAC11;
        font-size: 40px;
        font-weight: 700;
        font-size: 40px;
        line-height: 60px;
        letter-spacing: 5px;
    }
    .section_text {
        color: #ffffff;
         font-size: 40px;
        font-weight: 700;
        font-size: 40px;
        line-height: 60px;
        letter-spacing: 5px;
    }
    .download_link {
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
        margin-top: 20px;
    }
    .move_down{
        margin-top: 70px;
       

    }
    .section_CTA {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        margin-top: 20px;
    }
    .primary_button{
          background-color: #0FAC11;
                border: 1px solid #0FAC11;

        color: #ffffff;
        font-weight: 700;
         padding: 1.3em 3.5em;
        font-size: 12px;
        border-radius: 5px;
        cursor: pointer;
    }
      .primary_button:hover{
        background-color: #056406;
        transition: 0.3s;
        cursor: pointer;
         border: 1px solid #056406;
    }
    .secondary_button {
         background-color: transparent;
        padding: 1.3em 3.5em;
        cursor: pointer;
        border: 1px solid #0FAC11;
        border-radius: 5px;
        font-size: 12px;
        color: #0FAC11;
    }
      .secondary_button:hover{
        cursor: pointer;
        transition: 0.3s;
          border: 1px solid #ffffff;
          color: white;

    }
</style>