<script>
export default {
  name: "OnlineShop",
};
</script>

<template>
  <div class="container">
    <div class="col">
      <ul>
        <li>
          <a href="#"
            ><img
              src="../MainSection/img/ebay-logotan-2x-200x66.png"
              alt="Ebay"
          /></a>
        </li>
        <li>
          <a href="#"
            ><img
              src="../MainSection/img/audible-logotan-2x-200x66.png"
              alt="Audible"
          /></a>
        </li>
        <li>
          <a href="#"
            ><img
              src="../MainSection/img/bb-logotan-2x-200x66.png"
              alt="Barners&Noble"
          /></a>
        </li>

        <li>
          <a href="#"
            ><img
              src="../MainSection/img/kindlefire-logotan-2x-200x66.png"
              alt="Kindel Fire"
          /></a>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  background-color: #fef7e9;

  .col {
    width: var(--container-md);
    margin: auto;
    padding: 1.875rem 0;
  }
  ul {
    list-style: none;
    display: flex;
    justify-content: space-around;
  }
  img {
    height: 3.125rem;
  }
}
</style>
