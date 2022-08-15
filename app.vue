<script setup>
import HTTPSnippet from "httpsnippet";

const snippet = new HTTPSnippet({
  method: "GET",
  url: "https://www.google.de",
});
</script>

<template>
  <div class="hello">Hello Nuxt {{ snippet }}!</div>
</template>

<style scoped>
.hello {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 3rem;
  padding: 10rem;
}
</style>
