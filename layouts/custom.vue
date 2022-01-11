<template>
  <header>
    custom header
  </header>
  <div>
    <slot />
  </div>
  <footer>
    custom footer
  </footer>
</template>

<script>
export default {
  layout: "custom",
};
</script>