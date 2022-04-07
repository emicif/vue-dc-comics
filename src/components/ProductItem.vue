<template>
  <div class="card">
      <img :src="product.thumb" />
      <h3>{{product.series}}</h3>
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
 width: calc(100% / 6);
 height: 50%;
 margin-top: 60px;
 img {
  text-align: start;
 }
}

.card h3 {
  padding-left: 10px;
  font-size: 10px;
  color: white;
  text-align: start;
  text-transform: uppercase;
  font-size: 1rem;
}



</style>
