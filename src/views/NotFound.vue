<template>
  <div class="center">
    <h1>Not Found!</h1>
    <p>
      <a href="/">Go home?</a>
    </p>
  </div>
</template>

<script>
export default {
  name: 'NotFound',
}
</script>

<style scoped>
.center {
  margin: 15vw;
}

h1 {
  color: var(--border);
  font-size: 2em;
}

a {
  text-decoration: none;
  color: inherit;
}
a:hover {
  color: #42b983;
}
</style>
