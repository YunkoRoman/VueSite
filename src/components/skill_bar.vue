<template>
    <div class="general_skill_bar_box">
        <div class="skill_bar_box">
            <p class="H1_skill">My Skills</p>
            <div class="skill_bar">
                <div class="skill_bar_1">
                    <div class="HTML">
                        <p class="title">HTML</p>
                        <div class="graph_box">
                            <div class="graph">
                                <div class="HTML_graph_line"></div>
                            </div>
                            <span class="rate">70%</span>
                        </div>
                    </div>
                    <div class="CSS">
                        <p class="title">CSS</p>
                        <div class="graph_box">
                            <div class="graph">
                                <div class="CSS_graph_line"></div>
                            </div>
                            <span class="rate">60%</span>
                        </div>
                    </div>
                    <div class="JS">
                        <p class="title">JavaScript</p>
                        <div class="graph_box">
                            <div class="graph">
                                <div class="JS_graph_line"></div>
                            </div>
                            <span class="rate">75%</span>
                        </div>
                    </div>
                </div>
                <div class="skill_bar_2">
                    <div class="Node">
                        <p class="title">NODE.JS</p>
                        <div class="graph_box">
                            <div class="graph">
                                <div class="node_graph_line"></div>
                            </div>
                            <span class="rate">72%</span>
                        </div>
                    </div>
                    <div class="angular">
                        <p class="title">ANGULAR</p>
                        <div class="graph_box">
                            <div class="graph">
                                <div class="angular_graph_line"></div>
                            </div>
                            <span class="rate">50%</span>
                        </div>
                    </div>
                    <div class="vue">
                        <p class="title">VUE</p>
                        <div class="graph_box">
                            <div class="graph">
                                <div class="vue_graph_line"></div>
                            </div>
                            <span class="rate">50%</span>
                        </div>
                    </div>
                </div>
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