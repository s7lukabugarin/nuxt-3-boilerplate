<template>
    <transition>
      <NuxtPage />
    </transition>
</template>

<script setup>
import "./assets/styles/global.css";
</script>

<style>
.page-enter-from {
  opacity: 0;
  transform: translateY(-1000px);
}

.page-enter-active,
.page-leave-active {
  transition: all 0.5s;
}
.page-enter,
.page-leave-to {
  opacity: 0;
}
</style>
