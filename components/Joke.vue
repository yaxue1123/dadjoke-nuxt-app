<template>
  <nuxt-link :to="'jokes/' + id">
    <ul class="joke">
      <li>{{ joke }}</li>
    </ul>
  </nuxt-link>
</template>

<script>
export default {
  name: "Joke",
  props: ["joke", "id"]
};
</script>

<style>
</style>
