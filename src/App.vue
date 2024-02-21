<template>
  <div>
  <ConditionComponent />
  <EventHandlers/>
  <ForList/>
</div>
</template>

<script setup>
import ConditionComponent from './components/ConditionComponent.vue';
import EventHandlers from './components/EventHandlers.vue';
import ForList from './components/ForList.vue';



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
