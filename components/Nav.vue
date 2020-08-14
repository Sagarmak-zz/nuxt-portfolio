<template>
  <header class="text-2xl text-accent hover:text-teal-400 m-4 md:mx-8 fixed top-0 right-0">
    <button class="py-2 px-4" @click="$emit('nav-toggle-theme')">
      <i v-if="!isLightTheme" class="fas fa-sun"></i>
      <i v-if="isLightTheme" class="fas fa-moon"></i>
    </button>
  </header>
</template>
<script>
export default {
  name: "Nav",
  props: [
    "isLightTheme"
  ]
};
</script>
