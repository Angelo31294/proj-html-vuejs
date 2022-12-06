<script>
import AboutDamon from "./MainSection/AboutDamon.vue";
import OnlineShop from "./MainSection/OnlineShop.vue";
import AudioBook from "./MainSection/AudioBook.vue";
export default {
  name: "AppMain",
  components: {
    AboutDamon,
    OnlineShop,
    AudioBook,
  },
};
</script>

<template>
  <div class="container">
    <AboutDamon />
    <OnlineShop />
    <AudioBook />
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  margin: auto;
}
</style>
