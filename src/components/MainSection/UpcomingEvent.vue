<script>
export default {
  name: "UpcomingEvent",
};
</script>

<template>
  <div class="container">
    <div class="col">
      <div class="title">
        <h3>Upcoming Event</h3>
        <h5>MEET THE AUTHOR IN PERSON</h5>
      </div>
      <div class="cards">
        <div class="card">
          <img
            src="../MainSection/img/event-05-200x120.jpg"
            alt="Chicago Book Signing"
          />
          <div class="text">
            <h3>Chicago Book Signing</h3>
            <hr />
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit debitis
              laboriosam quaerat, magni eos soluta sint nesciunt.
            </p>
          </div>
        </div>
        <div class="card">
          <img
            src="../MainSection/img/event-04-200x120.jpg"
            alt="Meet & Greet With Amanda"
          />
          <div class="text">
            <h3>Meet & Greet With Amanda</h3>
            <hr />
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit debitis
              laboriosam quaerat, magni eos soluta sint nesciunt.
            </p>
          </div>
        </div>
        <div class="card">
          <img
            src="../MainSection/img/event-07-200x120.jpg"
            alt="Open Book: Dialogues"
          />
          <div class="text">
            <h3>Open Book: Dialogues</h3>
            <hr />
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit debitis
              laboriosam quaerat, magni eos soluta sint nesciunt.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  background-color: var(--sixth-color);
  padding: 5rem 0;

  .col {
    width: 62.5rem;
    margin: auto;

    .title {
      text-align: center;

      h3,
      h5 {
        margin-bottom: 1.25rem;
      }

      h3 {
        color: var(--first-color);
        font-size: 1.875rem;
      }

      h5 {
        color: var(--third-color);
      }
    }

    .cards {
      display: flex;
      justify-content: space-between;
      .card {
        width: 30%;
        background-color: var(--second-color);

        .text {
          padding: 0.625rem 1.25rem;
          text-align: center;
          h3 {
            color: var(--first-color);
          }

          p {
            color: var(--fourth-color);
          }

          hr {
            margin: 0.625rem 0;
            color: var(--fourth-color);
          }
        }

        img {
          width: 100%;
        }
      }
    }
  }
}
</style>
