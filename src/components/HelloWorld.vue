<template>
    <div>
        <el-button type="primary" @click="increment">{{ state.count }}</el-button>
        <div>这是一个新的demo</div>
    </div>
</template>

<script setup lang="ts">
import { ref, reactive } from 'vue';
defineProps<{ msg: string }>();
// 增加按钮
const state = reactive({ count: 0 });
const increment = () => {
    state.count++;
};
</script>

<style scoped>
a {
    color: #c9227e;
}

label {
    margin: 0 0.5em;
    font-weight: bold;
}

code {
    background-color: #eee;
    padding: 2px 4px;
    border-radius: 4px;
    color: #304455;
}
</style>
