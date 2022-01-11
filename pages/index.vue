<template>
    <!-- <span class="test">test</span>
    {{ test }}
    <NuxtWelcome /> -->
    <div class="wrapper">
      <NuxtLayout name="custom">
      <span class="test">
        test12342142
      </span>
      {{ data }}
      <img src="/images/bubica.jpg" alt="">
      <NuxtLink to="/my-page">My Page</NuxtLink>
    </NuxtLayout>
    </div>
</template>

<script setup>
const { data } = await useAsyncData('count', () => $fetch('/api/count'))
const test = useTest();
// import { defineComponent } from 'vue';

// export default defineComponent({
//   layout: false,
//   setup() {
//     const test = useTest();
//   },
// })
</script>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  layout: false,
})
</script>

<style scoped>
  .wrapper {
    background: orange;
  }
</style>

