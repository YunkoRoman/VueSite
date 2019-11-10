<template>
    <div class="general_box">
        <div class="communication_box">
            <div class="form_for_leave_message">
                <p class="h1_write">Leave a Message</p>
                <form action="" class="form_box">
                    <input type="text" class="name_inp" placeholder="Name:">
                    <input type="email" class="name_inp" placeholder="Email:">
                    <textarea type="text" class="message_inp" placeholder="Your text"></textarea>
                    <input type="button" value="Send message" class="button_inp" >
                </form>
            </div>
            <div class="transverse_line"></div>
            <div class=""></div>
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