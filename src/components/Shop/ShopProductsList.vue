<template>
  <div class="d-flex flex-row flex-wrap">
    <shop-products-items></shop-products-items>
    <shop-products-items></shop-products-items>
    <shop-products-items></shop-products-items>
    <shop-products-items></shop-products-items>
    <shop-products-items></shop-products-items>
    <shop-products-items></shop-products-items>
    <shop-products-items></shop-products-items>
  </div>
</template>

<script>
import ShopProductsItems from './ShopProtuctsItems.vue';

export default {
  components: {
    ShopProductsItems,
  },
};
</script>

<style>

</style>
