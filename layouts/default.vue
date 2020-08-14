<template>
  <div>
    <Nav />
    <Nuxt />
  </div>
</template>
<script>
import Nav from "@/components/Nav.vue";
export default {
  components: {
    Nav
  }
}
</script>
<style>
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

header {
  min-height: 10vh;
}
</style>
