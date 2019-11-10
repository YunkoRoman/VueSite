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
                <div class="box_Story_about_Education">
                    <div class="left_box_1">
                        <div>
                            <img src="@/assets/img/comment_left.png" alt="" class="img">
                        </div>
                        <div class="box_desc">
                            <div class="box_about_educt_left">
                                <p class="Educ_name">OktenWeb University</p>
                                <p class="Educ_date"> FEB 2019 - SEP 2019</p>
                                <p class="Educ_desc"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam
                                    animi dolorum </p>
                            </div>
                        </div>
                    </div>
                    <div class="box_stepLine">
                        <div class="around_ball"><span class="ball"></span></div>
                        <div class="vertical_line"></div>
                        <div class="around_ball"><span class="ball"></span></div>
                    </div>
                    <div class="right_box_1">
                        <div>
                            <img src="@/assets/img/comment_right.png" alt="" class="img1">
                        </div>
                        <div class="box_desc">
                            <div class="box_about_educt_right">
                                <p class="Educ_name">Lviv Polytechnic National University</p>
                                <p class="Educ_date"> sep 2013 - dec 2018</p>
                                <p class="Educ_desc"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam
                                    animi dolorum </p>
                            </div>
                        </div>
                    </div>

                </div>
                <div class="extra_line">
                    <div class="box_stepLine_next">
                        <div class="vertical_line_next"></div>
                    </div>
                </div>
                <div class="box_Story_about_Education">
                    <div class="left_box_1">
                        <div>
                            <img src="@/assets/img/comment_left.png" alt="" class="img">
                        </div>
                        <div class="box_desc">
                            <div class="box_about_educt_left">
                                <p class="Educ_name">OktenWeb University</p>
                                <p class="Educ_date"> FEB 2019 - SEP 2019</p>
                                <p class="Educ_desc"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam
                                    animi dolorum </p>
                            </div>
                        </div>
                    </div>
                    <div class="box_stepLine">
                        <div class="around_ball"><span class="ball"></span></div>
                        <div class="vertical_line"></div>
                        <div class="around_ball"><span class="ball"></span></div>
                    </div>
                    <div class="right_box_1">
                        <div>
                            <img src="@/assets/img/comment_right.png" alt="" class="img1">
                        </div>
                        <div class="box_desc">
                            <div class="box_about_educt_right">
                                <p class="Educ_name">Lviv Polytechnic National University</p>
                                <p class="Educ_date"> sep 2013 - dec 2018</p>
                                <p class="Educ_desc"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam
                                    animi dolorum </p>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
        <skill_bar></skill_bar>
        <message_form></message_form>
        <underline></underline>
        <footers></footers>

    </div>
</template>

<script>
    import underline from './underline'
    import skill_bar from './skill_bar'
    import message_form from './message_form'
    import footers from './footer'
    export default {
        name: "main",
        components: {
            underline,
            skill_bar,
            message_form,
            footers
        },

    }
</script>
<style scoped>
    @import "../assets/css/main.css";
</style>