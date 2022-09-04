<template >
    <div class="waitlist_container">
        <div class="form">
            <p class="form_header">Join our Wait List</p>
            <form class="form_input" action="">
                <div>
                 <label for="cars">*Name :</label>
                 <input id="name" required type="text" class="">
                </div>
                <div>
                    <label for="cars">*Email :</label>
                    <input id="email"  type="email" required class="">
                </div>
                <div>
                 <label for="cars">Where do you work :</label>
                 <input id="name" required type="text" class="">
                </div>
                <label for="cars">*Which would you prefer</label>
                <select id="cars">
                <option>Select one</option>
                <option value="Yes">Driver</option>
                <option value="Yes">Rider</option>
                <option value="both">Both</option>
                </select>
                <button class="primary_button">Join</button>
            </form>
        </div>
    </div>
</template>
<script setup>

</script>
<style scoped>

    .waitlist_container{
    background-image: url("@/assets/waitlist_bg.png");
     background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 100px 0;
    width: 100%;
    background-color: #038707;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 12px;
    margin: 100px 0;
    }
    .form{
        background-color: transparent;
        border: 1px solid #ffffff;
        padding: 50px;
        backdrop-filter: blur(10px);
        border-radius: 3%;
       
    }
    .form_header{
     text-align: center;
     color: white;
     font-size: 25px;
     font-weight: 600;
     margin-bottom: 30px;
    }
    input {
        background-color: transparent;
        border: 1px solid #ffffff;
        width: 100%;
        color: #A7A7A7;
        margin-top: 10px;
        margin-bottom: 10px;
        height: 45px;
        font-size: 16px;
        padding: 0 10px;
        font-weight: 400;
        font-size: 14px;
        line-height: 150%;
    }
    input:focus {
        border-radius: 0;
        outline: none;

    }
    .form_input {
        display: flex;
        flex-direction: column;
        color: #ffffff;
      
    }
      .primary_button {
        background-color: #0FAC11;
        border: none;
        color: #ffffff;
        font-weight: 700;
         padding: 1em 0;
        border-radius: 0;
        margin-top: 10px;
    }
     .primary_button:hover{
        background-color: #056406;
        transition: 0.5s;
        cursor: pointer;
    }
    select {
        background-color: transparent;
        border: 1px solid #ffffff;
        width: 100%;
        color: #ffffff;
        margin-top: 10px;
        margin-bottom: 30px;
        height: 50px;
        font-size: 13px;
        padding: 0 10px;
        font-weight: 400;
        line-height: 150%;
    }
    option{
        color: black;
        font-size: 13px;
    }
</style>