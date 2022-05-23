<template>
    <div>
        <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
        <HelloWorld_1 msg="Hello Vue 3 + TypeScript + Vite" />
        <span>23</span>
    </div>
</template>

<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue';
import HelloWorld_1 from './com/src/components/HelloWorld.vue';
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
