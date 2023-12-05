<template>
    <h1>Counter</h1>
    <div>{{ count }}</div>
    <button @click="countup">+</button>
</template>

<script setup>
const count = ref(0)

function countup() {
    count.value += 1
}
</script>