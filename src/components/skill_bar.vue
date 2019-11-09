<template>
    <div class="general_skill_bar_box">
        <div class="skill_bar_box">
            <p class="H1_skill">My Skills</p>
            <div class="skill_bar">
                <div class="skill_bar_1">
                    <div class="HTML">
                        <p id="title_HTML">HTML</p>
                        <div class="HTML_graph_box">
                            <div class="HTML_graph">
                                <div class="HTML_graph_line"></div>
                            </div>
                            <span class="rate">70%</span>
                        </div>
                    </div>
                    <div class="CSS">
                        <p id="title_CSS">CSS</p>
                        <div class="CSS_graph_box">
                            <div class="CSS_graph">
                                <div class="JS_graph_line"></div>
                            </div>
                            <span class="rate">60%</span>
                        </div>
                    </div>
                    <div class="JS">
                        <p id="title_JS">JavaScript</p>
                        <div class="JS_graph_box">
                            <div class="JS_graph">
                                <div class="JS_graph_line"></div>
                            </div>
                            <span class="rate">75%</span>
                        </div>
                    </div>
                </div>
                <div class="skill_bar_2"></div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "skill_bar"
    }
</script>

<style scoped>
    @import "../assets/css/skill_bar.css";
</style>