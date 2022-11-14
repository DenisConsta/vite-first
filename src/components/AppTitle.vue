<template>
  <div class="container">
    <h1> {{title}} </h1>
  </div>
</template>

<script>
export default {
  name: "AppTitle",
  data() {
    return {
      title: "La mia prima app con Vite!",
    };
  },
};
</script>

<style scoped>

  h1{
    color: blueviolet;
    font-size: 3rem;
    font-family: italic;
  }

</style>