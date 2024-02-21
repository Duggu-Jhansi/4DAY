<template>
<div>
    <button v-on:click="ClickEvent">Count</button>
    <p>{{ count }}</p>
    <button @click="Multiply">Multiply Number</button>
    <p>{{ mul }}</p>
</div>
</template>
<script setup>
import {ref} from  'vue'
const count=ref(0);
const mul=ref(1);
const ClickEvent=()=>{
count.value++;
}
const Multiply=()=>{
mul.value--;
}
</script>
<style>
</style>