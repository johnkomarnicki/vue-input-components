<template>
  <div>
    <BaseInput v-model="firstName" type="text" class="base-input" />

    <p>{{ firstName }}</p>
  </div>
</template>

<script setup>
import BaseInput from "./components/BaseInput.vue";
import { ref } from "vue";

const firstName = ref("");
</script>

<style>
#app {
  max-width: 450px;
  margin: 60px auto;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
