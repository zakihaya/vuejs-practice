<template>
  <div class="hello">
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
  export default {
    name: 'hello2',
    data() {
      return {
        message: 'ようこそ',
      };
    },
  };
</script>

<style scoped>
  h1 {
    color: red;
  }
</style>
