<template>
  <div id="app">
    <Header />
    <ProductPage />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import ProductPage from './components/ProductPage.vue';

export default {
  components: {
    Header,
    ProductPage,
  },
};
</script>

<style>
/* General styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
