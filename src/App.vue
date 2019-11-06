<template>
    <div class="box">
        <div class="filling">
            <Menu></Menu>
            <Main></Main>
        </div>
    </div>

</template>

<script>
    import menu from './components/menu'
    import main from './components/main'

    export default {

        components: {
            'Menu':menu,
            'Main':main
        }
    }
</script>

<style scoped>
 @import "./assets/css/App.css";
</style>
