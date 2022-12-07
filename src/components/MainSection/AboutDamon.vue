<script>
export default {
  name: "AboutDemon",
};
</script>

<template>
  <div class="col">
    <h2><em>More About Damon Vaughn</em></h2>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ipsa error
      molestias tenetur labore tempore soluta magni cum minima ea velit.
      Molestiae fugiat quasi quos quisquam illo, eum in ullam maiores!
    </p>
    <button>Meet The Author</button>
  </div>
</template>

<style lang="scss" scoped>
.col {
  text-align: center;
  width: 56.25rem;
  margin: auto;
  padding: 3.75rem 0;
}

h2,
p,
button {
  margin-bottom: 0.9375rem;
}

h2 {
  color: var(--third-color);
}

p {
  color: var(--first-color);
}

button {
  background-color: #49a987;
  color: var(--second-color);
  border: none;
  border-radius: 0.125rem;
  padding: 0.3125rem 0.625rem;
}
</style>
