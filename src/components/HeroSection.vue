<script>
export default {
  name: "HeroSection",
};
</script>

<template>
  <div class="container">
    <div class="title-author">
      <h1><em>Damon Vaughn</em></h1>
      <p>
        <strong>
          Best-selling author and the most influential public intellectual in
          the western world right now.
        </strong>
      </p>
      <h4><em>- The New York Times</em></h4>
      <div>
        <button class="btn"><i class="fa-solid fa-arrow-left"></i></button>
        <button class="btn"><i class="fa-solid fa-arrow-right"></i></button>
      </div>
    </div>
    <div class="amazon-shop">
      <div class="amazon-shop-left">
        <img src="../assets/audible-app-2x-200x209.png" alt="" />
      </div>
      <div class="amazon-shop-right">
        <h4>Lates Book Release</h4>
        <h5>D. VAUGHN AUTOBIOGRAPHY</h5>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="shop-button">
        <button class="btn-left">
          <i class="fa-brands fa-amazon"></i> Buy On Amazon
        </button>
        <button class="btn-right">
          <i class="fa-brands fa-apple"></i> Buy On AppStore
        </button>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.title-author {
  width: 31.25rem;
  height: 18.75rem;
  margin-left: 6.25rem;

  h1 {
    font-size: 4.375rem;
    color: var(--third-color);
  }

  p {
    font-size: 2.1875rem;
  }

  h4 {
    color: var(--fourth-color);
  }

  .btn {
    background-color: var(--first-color);
    color: var(--second-color);
    padding: 0.625rem;
    border: none;
    margin: 0.125rem;
  }
}

.amazon-shop {
  position: absolute;
  display: flex;
  flex-wrap: wrap;
  width: 25rem;
  height: 15.625rem;
  background-color: var(--second-color);
  top: 35%;
  left: calc(100% - 528px);

  h4 {
    color: var(--first-color);
  }

  h5 {
    color: var(--third-color);
  }

  p {
    font-size: 1rem;
    color: var(--first-color);
  }

  h4,
  h5,
  p {
    margin-bottom: 0.3125rem;
  }
}

.amazon-shop-left {
  img {
    width: 100%;
  }
}

.amazon-shop-right,
.amazon-shop-left {
  width: 50%;
  padding: 0.9375rem 1.25rem;
}

.shop-button {
  width: 100%;
  text-align: center;

  .btn-left,
  .btn-right {
    background-color: #f5fcfa;
    border: 1px solid #a4d2c2;
    padding: 0.4375rem 0.625rem;
  }
}

button {
  cursor: pointer;
}
</style>
