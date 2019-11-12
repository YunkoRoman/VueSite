<template>
    <div class="general_box">
        <a id="contacts"></a>
        <div class="communication_box">
            <div class="form_for_leave_message">
                <p class="h1_write">Leave a Message</p>
                <form action="" class="form_box">
                    <input type="text" class="name_inp" placeholder="Name:"  autocomplete="off">
                    <input type="email" class="name_inp" placeholder="Email:">
                    <textarea type="text" class="message_inp" placeholder="Your text"></textarea>
                    <input type="button" value="Send message" class="button_inp" >
                </form>
            </div>
            <div class="transverse_line"></div>
            <div class="other_info">
                <div class="Location_box">
                    <div class="location_img"></div>
                    <div class="desc_box">
                        <p class="info_name">Location</p>
                        <p class="info_desc">Lviv</p>
                    </div>
                </div>
                <div class="Email_box">
                    <div class="Email_img"></div>
                    <div class="desc_box">
                        <p class="info_name">Email</p>
                        <p class="info_desc">romanyunko1996@gmail.com</p>
                    </div>
                </div>
                <div class="Phone_box">
                    <div class="Phone_img"></div>
                    <div class="desc_box">
                        <p class="info_name">Call me</p>
                        <p class="info_desc">0932361952</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "message_form"
    }
</script>

<style scoped>
    @import "../assets/css/message_form.css";
</style>