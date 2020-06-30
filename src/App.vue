<template>
  <div id="app">
   <the-header></the-header>
   <div class="d-flex flex-row">
     <shop class="w-75 border bg-danger"></shop>
     <cart class="w-25 border bg-success"></cart>
   </div>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue';
import Shop from './components/Shop/Shop.vue';
import Cart from './components/Cart/Cart.vue';

export default {
  name: 'App',
  components: {
    TheHeader,
    Shop,
    Cart,
  }, // be carefull errreur de comma eslint = histoire de virgule.
};
</script>

<style>

</style>
