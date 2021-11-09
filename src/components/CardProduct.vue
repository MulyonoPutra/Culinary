<template name="component-name">
  <div>
    <h2>{{ product.name }}</h2>
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