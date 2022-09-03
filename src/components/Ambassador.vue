<template>
    <div class="ambassador_container">
        <div class="ambassador_writeup">
            <div>
                <p class="ambassador_header">Be a Greach Ambassador</p>
                <p class="ambassador_subtext">Interested in being  our Ambassador at your workplace? Sign-up your colleagues and get 10% off the cost of each of their first Greach ride</p>
            </div>
            <button class="primary_button">I'm Interested</button>
        </div>
        <img alt="phone mockup" class="web_img" src="@/assets/ambassador_img.png"/>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .ambassador_container {
        display: flex;
        flex-direction: row;
        padding: 35px 0px;
        gap: 216px;
        justify-content: space-between;
        align-items: center;
        width: 90%;
        margin: 0 auto;
        max-width: 1440px;
    }
    .ambassador_writeup {
        display: flex;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 0px;
        gap: 46px;
    }
    .ambassador_header {
        font-style: normal;
        font-weight: 700;
        font-size: 44px;
        line-height: 69px;
    }
    .ambassador_subtext {
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 36px;
        width: 502px;
        margin-top: 5px;
    }
      .primary_button{
        background-color: #0FAC11;
        border: 1px solid #0FAC11;
        color: #ffffff;
        font-weight: 700;
        padding: 1.3em 3.5em;
        border-radius: 5px;
        cursor: pointer;
    }
      .primary_button:hover{
        background-color: #056406;
        transition: 0.3s;
        cursor: pointer;
         border: 1px solid #056406;
    }
</style>
