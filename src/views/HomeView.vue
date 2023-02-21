<script setup lang="ts">
import TheWelcome from "../components/TheWelcome.vue";
import { onMounted } from "vue";
onMounted(() => {
  console.log("home view has mounted");
})
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template>
