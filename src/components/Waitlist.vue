<template >
    <div class="waitlist_container">
        <div class="form">
            <p class="form_header">Join our Wait List</p>
            <form class="form_input" action="">
                <div>
                 <label for="name">*Name :</label>
                 <input id="name"  v-model="selected.name" required type="text" class="">
                </div>
                <div>
                    <label for="email">*Email :</label>
                    <input id="email"  v-model="selected.email"  type="email" required class="">
                </div>
                <div>
                 <label for="work">Where do you work :</label>
                 <input id="work"  v-model="selected.work" required type="text" class="">
                </div>
                <div>
                    <label for="pow">*Which would you prefer</label>
                    <select id="pow" v-model="selected.owner">
                    <option disabled>Please select one</option>
                    <option>Driver</option>
                    <option>Rider</option>
                    <option>Both</option>
                    </select>
                </div>
                <button class="primary_button">Join</button>
            </form>
        </div>
    </div>
</template>
<script>
export default {
    data() {
    return {
      selected: {
        name:"",
        email:"",
        work:"",
        owner:""

      },

    }
  }
}
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

@media screen and (max-width: 1080px) {

        .waitlist_container{
    background-image: url("@/assets/waitlist_bg.png");
     background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 100px 0;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 12px;
    margin: 100px 0;
    }
}
    @media screen and (max-width: 700px) {
            .form{
        background-color: transparent;
        border: none;
        padding: 20px;
        backdrop-filter: none;
        border-radius: 3%;
       
    }
    }
</style>