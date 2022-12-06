<script>
import HeroSection from "./HeroSection.vue";
export default {
  name: "NabBar",
  components: {
    HeroSection,
  },
  data() {
    return {
      links: [
        {
          href: "#",
          label: "Home",
          active: true,
        },
        {
          href: "#",
          label: "About Me",
          active: false,
        },
        {
          href: "#",
          label: "Testimonials",
          active: false,
        },
        {
          href: "#",
          label: "My Blog",
          active: false,
        },
        {
          href: "#",
          label: "Meetups",
          active: false,
        },
        {
          href: "#",
          label: "Shop",
          active: false,
        },
        {
          href: "#",
          label: "Contact Me",
          active: false,
        },
        {
          href: "#",
          label: "Carrello",
          active: false,
        },
      ],
    };
  },
  methods: {
    changeLink(index) {
      this.links.forEach((elm, i) => {
        if (i === index) {
          elm.active = true;
        } else {
          elm.active = false;
        }
      });
    },
  },
};
</script>

<template>
  <div class="container nav-bar">
    <img src="../assets/author-logo-round.png" alt="logo" />
    <ul>
      <li
        v-for="(link, index) in links"
        :class="{ active: link.active }"
        @click.prevent="changeLink(index)"
      >
        <a :href="link.href">
          {{ link.label }}
        </a>
      </li>
    </ul>
  </div>
  <HeroSection />
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  margin: auto;
  display: flex;
  justify-content: space-between;
  background-color: transparent;
}

img {
  width: 7.5rem;
  margin-left: 100px;
}

ul {
  display: flex;
  list-style: none;
  margin-right: 1.25rem;

  li {
    padding: 1.25rem 0.625rem;
  }
}
.active {
  color: var(--third-color);
  border-top: 0.1875rem solid var(--third-color);
}
a {
  text-decoration: none;
  color: inherit;
  font-size: 0.75rem;
}
</style>
