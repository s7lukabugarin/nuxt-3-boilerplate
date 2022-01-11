<template>
  <div class="wrapper">
    <!-- <span class="test">test</span>
    {{ test }}
    <NuxtWelcome /> -->
    <NuxtLayout name="custom">
      dsadsadsa
    </NuxtLayout>
    <!-- dasdas -->
  </div>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  setup() {
    const test = useTest();
  },
})
</script>

<style scoped>
.wrapper {
  background: purple;
  height: 100vh;
}
</style>

