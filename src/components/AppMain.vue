<script>
import AboutDamon from "./MainSection/AboutDamon.vue";
import OnlineShop from "./MainSection/OnlineShop.vue";
import AudioBook from "./MainSection/AudioBook.vue";
import CriticsSection from "./MainSection/CriticsSection.vue";
import UpcomingEvent from "./MainSection/UpcomingEvent.vue";
import NewsLetter from "./MainSection/NewsLetter.vue";
import MoreAboutDV from "./MainSection/MoreAboutDV.vue";
import RecentArticle from "./MainSection/RecentArticle.vue";
export default {
  name: "AppMain",
  components: {
    AboutDamon,
    OnlineShop,
    AudioBook,
    CriticsSection,
    UpcomingEvent,
    NewsLetter,
    MoreAboutDV,
    RecentArticle,
  },
};
</script>

<template>
  <div class="container">
    <AboutDamon />
    <OnlineShop />
    <AudioBook />
    <CriticsSection />
    <UpcomingEvent />
    <NewsLetter />
    <MoreAboutDV />
    <RecentArticle />
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  margin: auto;
}
</style>
