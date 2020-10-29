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
    return {
      products: [
        { name: "Banana Skin", price: 20 },
        { name: "Shiny Star", price: 40 },
        { name: "Green Shells", price: 60 },
        { name: "Red Shells", price: 80 },
      ],
    };
  },
};
</script>

<style>
</style>
