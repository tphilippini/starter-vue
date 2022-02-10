<script setup>
import Counter from './components/Counter.vue'
</script>

<template>
  <div class="container">
    <h1 class="title">Starter Vue App</h1>
    <p class="subtitle">with Vite.js, Vue.js, Sass</p>
    <Counter />
  </div>
</template>

<style lang="scss">
  .container {
    text-align: center;
  }

  .title {
    color: $primary;
    margin-top: 1em;
  }

  .subtitle {
    font-size: 12px;
    margin-bottom: 1em;
  }
</style>
