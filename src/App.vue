<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
    <ProdctListOne :products="products" />
    <ProductListTwo :products="products" />
  </div>
</template>

<script>
import ProdctListOne from "./components/ProdctListOne";
import ProductListTwo from "./components/ProductListTwo";

export default {
  components: {
    ProdctListOne,
    ProductListTwo,
  },
  data() {
    return {};
  },
};
</script>

<style>
</style>
