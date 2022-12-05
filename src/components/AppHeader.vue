<script>
import NavBar from "./NavBar.vue";
export default {
  name: "AppHeader",
  components: {
    NavBar,
  },
};
</script>

<template>
  <header class="container">
    <NavBar />
    <HeroSection />
  </header>
</template>

<style lang="scss" scoped>
.container {
  margin: auto;
  width: 120rem;
  height: 50rem;
  background-image: url(../assets/hero-07-2x.jpg);
  background-position: center;
  background-size: cover;
}
</style>
