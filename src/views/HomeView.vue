<script setup>
import { defineAsyncComponent } from "vue";

const TheWelcome = defineAsyncComponent(() =>
  import("../components/TheWelcome.vue")
);
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template>
