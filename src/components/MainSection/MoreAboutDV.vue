<script>
export default {
  name: "MoreAboutDV",
};
</script>

<template>
  <div class="container">
    <div class="col">
      <div class="title">
        <h3>Dig Little Deeper Into Damon Vaughn</h3>
        <h5>FIND OUT MORE ABOUT THE AUTHOR HIMSELF</h5>
      </div>
      <div class="cards">
        <div class="card1">
          <div class="text">
            <h4>About Me</h4>
            <hr />
            <p>Vestibulum ante ipsum primis</p>
          </div>
        </div>
        <div class="card2">
          <div class="text">
            <h4>My Lates Book</h4>
            <hr />
            <p>Vestibulum ante ipsum primis</p>
          </div>
        </div>
        <div class="card3">
          <div class="text">
            <h4>Book Signing</h4>
            <hr />
            <p>Vestibulum ante ipsum primis</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  padding: 5rem 0;

  .col {
    width: 62.5rem;
    margin: auto;
  }

  .title {
    text-align: center;

    h3,
    h5 {
      margin-bottom: 1.25rem;
    }

    h3 {
      font-size: 1.875rem;
      color: var(--first-color);
    }

    h5 {
      font-size: 0.75rem;
      color: var(--fifth-color);
    }
  }

  .cards {
    display: flex;
    justify-content: space-between;

    .card1 {
      background-image: url(../MainSection/img/box-1.jpg);
    }
    .card2 {
      background-image: url(../MainSection/img/box-4.jpg);
    }
    .card3 {
      background-image: url(../MainSection/img/box-3.jpg);
    }

    .card1,
    .card2,
    .card3 {
      width: 30%;
      height: 25rem;
      border-bottom-right-radius: 1.25rem;
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      text-align: center;
      display: flex;
      flex-direction: column;

      .text {
        margin-top: auto;
        padding: 1.875rem;

        h4 {
          font-size: 1.5rem;
        }

        hr {
          width: 3.125rem;
          margin: 1.25rem auto;
        }

        p {
          color: var(--third-color);
          font-size: 0.75rem;
        }
      }
    }
  }
}
</style>
