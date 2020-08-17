<template>
  <header
    class="text-2xl text-accent hover:text-teal-400 transition duration-300 ease-in-out m-4 md:mx-8 fixed top-0 right-0"
  >
    <button class="theme-switcher py-2 px-4" @click="onThemeSwitcherClick">
      <transition name="fade" mode="out-in">
        <i v-if="!isLightTheme" key="1" class="fas fa-sun"></i>
        <i v-if="isLightTheme" key="2" class="fas fa-moon"></i>
      </transition>
    </button>
  </header>
</template>
<script>
export default {
  name: "Nav",
  props: ["isLightTheme"],
  methods: {
    onThemeSwitcherClick() {
      this.$emit("nav-toggle-theme");
      console.log(this.$refs, this.$refs.themeSwitcher);
    }
  }
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
