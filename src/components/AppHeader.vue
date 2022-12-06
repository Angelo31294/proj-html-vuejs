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
  </header>
</template>

<style lang="scss" scoped>
.container {
  margin: auto;
  width: var(--container-size);
  height: 31.25rem;
  background-image: url(../assets/hero-07-2x.jpg);
  background-position: center;
  background-size: cover;
}
</style>
