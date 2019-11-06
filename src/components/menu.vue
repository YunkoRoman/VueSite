<template>
    <div class="menu_box">
        <div class="name_box">
            <img src="@/assets/photo/I.jpg" alt="" width="100%" height="100%">

            <p class="name">Yunko Roman</p>

            <p class="profession">Full Stack Developer</p>

        </div>
        <div class="btn_nav_box">
            <button class="btn"><span>Home</span></button>
            <button class="btn"><span>About Me</span></button>
            <button class="btn"><span>Education</span></button>
            <button class="btn"><span> Skills</span></button>
            <button class="btn"><span> Contacts</span></button>
        </div>
    </div>
</template>

<script>
    export default {
        name: "menu",

    }

</script>

<style scoped>
    @import "../assets/css/menu.css";
</style>