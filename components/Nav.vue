<template>
  <header
    class="text-2xl text-accent hover:text-teal-400 transition duration-300 ease-in-out m-4 md:mx-8 fixed top-0 right-0"
  >
    <div class="cursor-pointer py-2 px-4" @click="$emit('nav-toggle-theme')">
      <transition name="fade" mode="out-in">
        <!-- <img v-if="!isLightTheme" key="1" src="../assets/icons/sun.svg" alt="logo" class="icon w-8 hover:opacity-75 transition-opacity duration-150 ease-in-out" />
        <img v-if="isLightTheme" key="2" src="../assets/icons/moon.svg" alt="logo" class="icon w-8 hover:opacity-75 transition-opacity duration-150 ease-in-out" /> -->
        <i v-if="!isLightTheme" key="1" class="fas fa-sun"></i>
        <i v-if="isLightTheme" key="2" class="fas fa-moon"></i>
      </transition>
    </div>
  </header>
</template>
<script>
export default {
  name: "Nav",
  props: ["isLightTheme"]
};
</script>
<style>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.3s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}
</style>
