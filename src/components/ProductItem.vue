<template>
  <div class="card">
      <img :src="product.thumb" />
      <h2>{{product.series}}</h2>
  </div>
</template>

<script>
export default {
  name: 'ProductItem',
  props: {
    product: Object
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.card {
 border: 1px solid grey;
 text-align: center;
}


</style>
