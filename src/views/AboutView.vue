<script setup>
import { defineAsyncComponent } from "vue";

const TheWelcome = defineAsyncComponent(() =>
  import("../components/TheWelcome.vue")
);
</script>

<template>
  <div class="about">
    <h1>This is an about page</h1>
    <TheWelcome />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
