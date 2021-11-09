<template>
  <div class="card shadow card-product">
    <img :src=" 'assets/images/' + product.images " class="card-img-top" alt="..." />
    <div class="card-body">
      <h5 class="card-title">{{ product.name }}</h5>
      <p
        class="card-text"
      >Harga : Rp. {{ product.price }}</p>
      <router-link class="btn btn-success" :to="'/foods/'+product.id">Pesan</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "CardProduct",
  props: ["product"],
};
</script>

<style>
</style>