<template>
    <div class="main_box">
        <div class="main_box_head">
            <img src="@/assets/img/Layer_1.png" alt="" width="100%" height="100%">
            <div class="writing">
                <p class="H1_writing">Lets Make Something Great</p>
                <p class="H2_writing">Lorem ipsum dolor sit amet, consectetur adipisicing elit. A assumenda atque
                    consectetur debitis dicta dolore ducimus eaque fuga illum libero, nobis, nostrum numquam praesentium
                    quam quia repudiandae ullam vero voluptatibus.
                </p>
                <button class="btn_writing">
                    <p>Hire Me!</p>
                </button>
            </div>
        </div>
        <div class="main_box_aboutMe">
            <div class="my_description">
                <p class="H1_about">About Me</p>
                <p class="description_about"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus,
                    adipisci, animi consectetur </p>
                <div class="info_about">
                    <p class="info-about-descript"><span class="info-about-descript_h1">Name:</span><span> Roman</span>
                    </p>
                    <p class="info-about-descript"><span
                            class="info-about-descript_h1">Age:</span><span> 23 years</span></p>
                    <p class="info-about-descript"><span class="info-about-descript_h1">Email:</span><span> </span></p>
                    <p class="info-about-descript"><span class="info-about-descript_h1">WEB:</span><span> </span></p>
                    <p class="info-about-descript"><span class="info-about-descript_h1">Address:</span><span> </span>
                    </p>
                </div>
            </div>
            <div class="my_photo">
                <img src="@/assets/photo/man.png" alt="" max-width="321px" max-height="464px">
            </div>
        </div>
        <underline></underline>
        <div class="main_box_Education">
            <div class="my_description_Education">
                <p class="H1_about">Education</p>
                <div class="box1_Story_about_Education">
                    <div class="left_box_1">
                        <img src="@/assets/img/comment_left.png" alt="">
                        <div class="left_box_1_desc">sdfsdf</div>
                    </div>
                    <div class="box_stepLine">
                        <div class="around_ball"><span class="ball"></span></div>
                        <div class="vertical_line"></div>
                        <div class="around_ball"><span class="ball"></span></div>
                    </div>
                    <div class="right_box_1"><img src="@/assets/img/comment_right.png" alt=""></div>

                </div>


            </div>

        </div>
    </div>
</template>

<script>
    import underline from './underline'

    export default {
        name: "main",
        components: {underline},

    }
</script>
<style scoped>
    @import "../assets/css/main.css";
</style>