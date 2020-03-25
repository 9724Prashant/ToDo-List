<template>
    <div id="app">
        <ToDoList/>
    </div>
</template>

<script>
    import ToDoList from './components/ToDoList.vue'

    export default {
        name: 'App',
        components: {
            ToDoList
        }
    }
</script>

<style lang="scss">
    @import url('https://use.fontawesome.com/releases/v5.7.2/css/all.css');

    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        font-size: 1rem;
        color: #333;
        width: 100%;
        max-width: 768px;
    }

    body {
        margin: 0;
        padding: 0;
        width: 100%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: flex-start;
        background: linear-gradient(to bottom right, #c13b9a, #d99ac9);
    }
</style>
