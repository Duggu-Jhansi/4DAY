<template>
<div>
    <h3>Conditional Rendering</h3>
    <div v-if="Grade===A">Good Student</div>
    <div v-else-if="Grade===B">AVg Student</div>
    <div v-else-if="Grade===C">Dull Student</div>
    <div v-else>Topper</div>


</div>
</template>
<script setup>
import {ref} from 'vue'
const Grade=ref('');
</script>
<style>
</style>