<template>
    <div class="menu_box">
        <div class="name_box">
            <img src="@/assets/photo/I.jpg" alt="" width="100%" height="100%">

            <p class="name">Yunko Roman</p>

            <p class="profession">Full Stack Developer</p>

        </div>
        <div class="btn_nav_box">
            <a href="#" v-scroll-to="'#home'" class="btn"><span class="btn_name">Home</span></a>
            <a href="#" v-scroll-to="'#aboutMe'" class="btn"><span class="btn_name">About Me</span></a>
            <a href="#" v-scroll-to="'#education'" class="btn"><span class="btn_name">Education</span></a>
            <a href="#" v-scroll-to="'#skills'" class="btn"><span class="btn_name">Skills</span></a>
            <a href="#" v-scroll-to="'#contacts'" class="btn"><span class="btn_name">Contacts</span></a>
        </div>
    </div>
</template>

<script>
    import Vue  from 'vue'
    import VueScrollTo from 'vue-scrollto'
    Vue.use(VueScrollTo);
    export default {
        name: "menu",

    }

</script>

<style scoped>
    @import "../assets/css/menu.css";
</style>