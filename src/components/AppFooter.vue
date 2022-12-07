<script>
export default {
  name: "AppFooter",
};
</script>

<template>
  <div class="container">
    <div class="col">
      <img src="../assets/author-logo-round.png" alt="logo" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  margin: auto;
  background-image: url(../assets/hero-07-2x.jpg);
  background-position: initial;
  background-repeat: no-repeat;
  background-size: cover;
  padding-top: 6.25rem;
}

img {
  max-width: 6.25rem;
  margin-left: 6.25rem;
}
</style>
