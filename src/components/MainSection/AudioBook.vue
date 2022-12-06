<script>
export default {
  name: "AudioBook",
};
</script>

<template>
  <div class="container">
    <div class="col">
      <div class="col-left">
        <img
          src="../MainSection/img/audible-app-2x-400x418.png"
          alt="Audible"
        />
      </div>
      <div class="col-right">
        <h2>New Audiobook</h2>
        <h5>NO TIME TO READ? NO PROBLEM. LISTEN TO IT</h5>
        <P>
          <em
            >Lorem ipsum dolor, sit amet consectetur adipisicing elit. Placeat
            officiis expedita alias eius molestias fugit!</em
          >
        </P>
        <div class="links-shop">
          <img src="../MainSection/img/audible-logo.png" alt="Audible" />
          <img src="../MainSection/img/bn-logo-tall.png" alt="Barners&Nobles" />
          <img src="../MainSection/img/kindle-logo-tall.png" alt="kindel" />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  background-image: url(../MainSection/img/banner.jpg);
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  padding-top: 3.125rem;

  .col {
    display: flex;
    width: var(--container-md);
    margin: auto;
    padding: 0 3.125rem;

    .col-left,
    .col-right {
      width: 50%;
      text-align: center;
    }

    .col-right {
      padding-top: 12.5rem;

      h2,
      h5,
      p {
        margin-bottom: 1.25rem;
      }

      h5 {
        color: var(--third-color);
      }

      p {
        color: var(--fourth-color);
        font-size: 0.75rem;
      }
      img {
        height: 2.1875rem;
        margin: 0 0.625rem;
      }
    }
  }
}
</style>
