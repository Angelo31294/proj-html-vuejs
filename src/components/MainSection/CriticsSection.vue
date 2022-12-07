<script>
export default {
  name: "CriticsSection",
};
</script>

<template>
  <div class="container">
    <div class="col">
      <div class="col-header">
        <div class="titles">
          <h3>What The Critics Say</h3>
          <h6>TESTIMONIALS FROM AROUND THE WORLD</h6>
        </div>
        <div class="button">
          <button>Read All The Testimonials</button>
        </div>
      </div>
      <div class="col-left">
        <div class="text">
          <h3>Best Author Of His Generation</h3>
          <hr />
          <p>This book will change your perspective on life</p>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptas
            quasi officia molestias eos dignissimos dolor dicta, alias similique
            aliquid quae, quo doloribus nemo? Mollitia omnis fugiat velit aut,
            tempora sequi.
          </p>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptas
            quasi officia molestias eos dignissimos dolor dicta, alias similique
            aliquid quae, quo doloribus nemo? Mollitia omnis fugiat velit aut,
            tempora sequi.
          </p>
          <img
            src="../MainSection/img/nytimes-logo-white-xsmall.png"
            alt="NYTLogo"
          />
          <span
            ><small> Justine Kilpatrick, </small>
            <small class="green"> The New York Times </small></span
          >
          <span></span>
        </div>
      </div>
      <div class="col-rigth">
        <div class="card">
          <div class="card-text">
            <h4><strong>A True Masterpiece, Bravo!</strong></h4>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam,
              corrupti? Sequi aspernatur beatae perspiciatis harum illo fugit
              dolorem voluptatem officiis.
            </p>
          </div>
          <div class="testimonials">
            <img
              src="../MainSection/img/theguardian-xsmall.png"
              alt="TheGuardinaLogo"
            />
            <span
              ><small class="grey"> Gerald Hendley, </small
              ><small> The Guardian </small></span
            >
          </div>
          <div class="card-text">
            <h4><strong>A True Masterpiece, Bravo!</strong></h4>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam,
              corrupti? Sequi aspernatur beatae perspiciatis harum illo fugit
              dolorem voluptatem officiis.
            </p>
          </div>
          <div class="testimonials">
            <img
              src="../MainSection/img/globe-xsmall.png"
              alt="TheGuardinaLogo"
            />
            <span
              ><small class="grey"> Mary Maxey, </small
              ><small> The Globe and Mail </small></span
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: var(--container-size);
  padding: 4.6875rem 0;

  .col {
    display: flex;
    flex-wrap: wrap;
    width: 56.25rem;
    margin: auto;

    .col-header {
      width: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;

      .titles {
        color: var(--first-color);

        h3 {
          font-size: 2.25rem;
        }

        h6 {
          color: var(--fifth-color);
          padding: 0.625rem 0;
        }
      }

      button {
        background-color: var(--third-color);
        color: var(--second-color);
        font-size: 0.625rem;
        padding: 0.3125rem 0.625rem;
        border: none;
        border-radius: 0.125rem;
        text-align: center;
        cursor: pointer;
      }
    }

    .col-left {
      width: 60%;
      background-image: url(../MainSection/img/testimonial2-2x.jpg);
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      padding: 2.5rem;
      border-bottom-right-radius: 1.875rem;

      h3,
      hr,
      p {
        margin-bottom: 0.9375rem;
      }

      h3 {
        font-size: 1.875rem;
      }

      hr {
        color: rgba($color: #a1a1a1, $alpha: 0.5);
      }

      span {
        font-size: 0.75rem;
      }
    }

    .col-rigth {
      width: 40%;
      padding-left: 5rem;

      .card {
        .card-text {
          text-align: center;
          background-color: var(--sixth-color);
          padding: 1.25rem;

          h4 {
            font-size: 1.125rem;
            margin-bottom: 0.625rem;
            color: var(--first-color);
          }

          p {
            font-size: 0.875rem;
            color: var(--fourth-color);
          }
        }
        .testimonials {
          display: flex;
          align-items: center;
          text-align: left;
          padding-top: 0.625rem;
          margin-bottom: 1.25rem;
          color: var(--first-color);
        }
      }
    }
  }
}
img {
  width: 0.9375rem;
  margin-right: 0.625rem;
}
.green {
  color: var(--fifth-color);
}

.grey {
  color: var(--fourth-color);
}
</style>
