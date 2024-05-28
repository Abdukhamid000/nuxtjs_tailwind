<template>
  <div>
    <h1 class="text-red-200">Welcome</h1>
    INDEX PAGE {{ data }}
  </div>
</template>

<script setup lang="ts">
import { ref } from "vue";

const data = ref("DATA");
</script>

<style scoped></style>
