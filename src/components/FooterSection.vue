<template>
    <div class="footer_section">
        <div class="footer_container">
            <div class="left_div">
                <div class="logo_div">
                <img alt="foter Img" class="" src="@/assets/footer_logo.svg"/>
                <h4 class="logo_div_text">Greach</h4>
                </div>
                <p class="company_description">Lörem ipsum od ohet dilogi. Bell trabel, samuligt, ohöbel utom diska. Jinesade bel när feras redorade i belogi. FAR paratyp i muvåning, och pesask vyfisat. Viktiga poddradio har un mad och inde. </p>
                <div class="download_link">
                    <a href="#"><img alt="apple logo" src="@/assets/appstore.svg"/></a>
                    <a href="#"><img alt="play store logo" src="@/assets/googleplay.svg"/></a>
                </div>
            </div>
            <div class="footer_contact">
                <h3 class="contact_div_text">Contact </h3>
                <div class="contact_info">
                    <img alt="apple logo" src="@/assets/Frame1.svg" /> 
                    <a href="#"> (406) 555-0120</a>
                </div>
                <div class="contact_info">
                    <img alt="apple logo" src="@/assets/email.svg" /> 
                    <a href="#">  help123@greach.co</a>
                </div>
                <div class="contact_info">
                    <img alt="apple logo" src="@/assets/Frame3.svg" />
                    <a href="#"> 2972 Westheimer Rd. Santa Ana, Illinois 85486 </a>
                </div>
            </div>
        </div>
            <hr class="line">
        <div class="last_section">
            <img alt="apple logo" src="@/one.svg" />
            <div class="">
                <img alt="apple logo" src="@/assets/facebook.svg" />
                <img alt="apple logo" src="@/assets/twitter.svg" />
                <img alt="apple logo" src="@/assets/linkedin.svg" />
                <img alt="apple logo" src="@/assets/instagram.svg" />
            </div>

        </div>

    </div>
</template>
<script setup>

</script>
<style scoped>
    .line {
        width: 90%;
        height: 1px;
        background-color: #202020;
        border: red;
        margin: 20px auto;
    }
    .last_section {
        display: flex;
        justify-content: space-around;
        /* width: 50%; */
        margin: 30px auto 0;
    }
    .footer_section {
        background-color: #000000;
        display: block;
       padding: 50px 0;
       margin-top: 80px;
       
    }
    .footer_container {
        color: #cecece;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
    }
    .footer_contact {
        display: flex;
        flex-direction: column;
        gap: 23px;
    }
    .logo_div_text {
        font-weight: 700;
        font-size: 32px;
        margin: 10px;
    }
    .logo_div {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .footer_container p {
        font: 12px;
        font-weight: 300;
        font-size: 14px;
        line-height: 24px;
    }
    .left_div {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        gap: 23px;
    }
    .contact_info {
        display: flex;
        flex-direction: row;
        justify-content: start;
        align-items: center;
    }
    .contact_info img {
        margin: 5px;
    }
    a {
        color: #cecece;
         font: 12px;
        font-weight: 300;
        font-size: 14px;
        line-height: 24px;
    }
    .company_description {
        width: 371px;
    }
    .download_link {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        gap: 20px;
    }
@media screen and (max-width: 1080px) {
      .footer_container {
        color: #cecece;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
     .footer_contact {
        display: flex;
        flex-direction: column;
        justify-content: start;
        align-items: flex-start;
        gap: 10px;
    }
}
</style>