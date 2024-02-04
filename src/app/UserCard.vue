<script>
export default {
  props: {
    name: String,
  },
};
</script>

<template>
  <div class="card-container">{{ name }}</div>
</template>

<style>
.card-container {
  background-color: bisque;
}
</style>
