<script>
export default {
  name: "RecentArticle",
};
</script>

<template>
  <div class="container">
    <div class="col">
      <div class="header-col">
        <div class="title">
          <h3>Recent Articles</h3>
          <h5>READ THE LATEST ENTIRIES</h5>
        </div>
        <div class="button"><button>All Articles</button></div>
      </div>
      <div class="col-main">
        <div class="col-left">
          <div class="card-left">
            <img src="../MainSection/img/20-Tips-600x353.jpg" alt="20tips" />
            <h4>20 Creativity Tips</h4>
            <span
              ><small
                >By admin | october 24th 2019 | Categories: Event, Tips &
                Tricks</small
              ></span
            >
            <p>
              Perferendis et, nemo eaque eligendi numquam consequatur modi
              impedit perspiciatis quod minima ad corporis odio.
            </p>
          </div>
        </div>
        <div class="col-rigth">
          <div class="card1">
            <img src="../MainSection/img/thumb-08-2x-320x202.jpg" alt="thumb" />
            <h4>What's On Your Booklist?</h4>
            <span><small>october 24th 2019 | 0 comments</small></span>
          </div>
          <div class="card2">
            <img src="../MainSection/img/thumb-13-2x-320x202.jpg" alt="thumb" />
            <h4>Instanbul Travel Guide</h4>
            <span><small>october 24th 2019 | 0 comments</small></span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  padding: 6.25rem 0;
  background-color: var(--sixth-color);
  color: var(--first-color);

  .col {
    width: 62.5rem;
    margin: auto;

    .header-col {
      width: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 1.25rem;

      h3 {
        font-size: 1.5rem;
        margin-bottom: 1.25rem;
      }

      h5 {
        font-size: 0.75rem;
        color: var(--fifth-color);
      }

      button {
        background-color: var(--third-color);
        border: none;
        border-radius: 0.125rem;
        padding: 0.625rem 1.875rem;
        color: var(--second-color);
        font-size: 0.5rem;
        cursor: pointer;
      }
    }

    .col-main {
      display: flex;
      justify-content: space-between;

      .col-left {
        width: 65%;

        .card-left {
          background-color: var(--second-color);
          padding: 1.25rem;
          color: var(--first-color);

          h4,
          p {
            margin-top: 0.625rem;
          }
        }
      }

      .col-rigth {
        width: 30%;
        background-color: var(--second-color);
        padding: 1.25rem;
      }

      .card1 {
        margin-bottom: 1.25rem;
      }
    }
  }
}

span,
p {
  font-size: 0.625rem;
}

img {
  width: 100%;
}
</style>
