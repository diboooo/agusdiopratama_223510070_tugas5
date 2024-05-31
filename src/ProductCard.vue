<template>
    <div class="card">
      <img class="card-img-top" :src="product.image" alt="Product image">
      <div class="card-body">
        <h5 class="card-title">{{ product.title }}</h5>
        <p class="card-text">{{ product.description }}</p>
        <a href="#" class="btn btn-primary">Buy Now</a>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'ProductCard',
    props: {
      product: Object
    }
  };
  </script>
  
  <style>
  .card {
    width: 18rem;
    margin: 10px;
  }
  </style>

