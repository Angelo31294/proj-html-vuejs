<script>
export default {
  name: "NewsLetter",
};
</script>

<template>
  <div class="container">
    <div class="col">
      <h3>Subscribe To My Newsletter</h3>
      <h5>BE NOTIFIED ABOUT BOOK SIGNING TOUR DATES</h5>
      <form>
        <input type="email" placeholder="insert your email ...*" />
        <button>Subscribe</button>
      </form>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Lorem ipsum
        dolor sit amet, consectetur adipisicing elit.
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  background-image: url(../MainSection/img/banner-2.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  padding: 7.5rem 0;

  .col {
    width: 18.75rem;
    margin: auto;
    text-align: center;

    h3,
    h5,
    form,
    p {
      padding-bottom: 1.25rem;
    }

    h3 {
      font-size: 1.875rem;
    }

    h5 {
      font-size: 0.75rem;
      color: var(--third-color);
    }

    p {
      font-size: 0.625rem;
      color: var(--fourth-color);
    }

    form {
      display: flex;
      justify-content: space-between;

      input {
        padding: 0.3125rem 0.625rem;
      }

      button {
        padding: 0.625rem;
        background-color: var(--fifth-color);
        color: var(--second-color);
        cursor: pointer;
      }

      input,
      button {
        border-radius: 0.1875rem;
      }
    }
  }
}
</style>
