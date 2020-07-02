<template>
  <div class="w-25 p-3 border">
   <div class="d-flex justify-content-center">
     <img style="height:150px" :src="product.img">
   </div>
   <div>
     <h3 class="text-center">{{ product.title }}</h3>
     <hr>
   </div>
   <div>
     <p class="text-justify">{{ product.description }}</p>
   </div>
   <div class="d-flex flex-row">
     <span>{{ product.price }}</span>
    </div>
    <div class="d-flex justify-content-end">
      <button class="btn btn-primary btn-sm">Buy</button>
    </div>
  </div>
</template>

<script>

export default {
  data() {
    return {
      product: {
        img: 'https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRBs97tfNflmA8MzfRuLKnL5q2yyBLCLIxGdjI2B6UAX8quRKZiVHpZJ1q9arQ&usqp=CAc',
        title: 'Last of us 2',
        description: 'Vivre dans une communauté florissante de survivants leur a permis de connaître la paix et la stabilité en dépit de la menace constante des infectés et des survivants désespérés.',
        price: '59,99€',
      },
    };
  },
};
</script>

<style>
  .product{
    height: 400px;
  }
  p{
    font-size: 12px;
  }
</style>
