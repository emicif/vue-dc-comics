<template>
    <main>
      <div class="container">
        <ProductItem v-for="(item, index) in products" :key="index" :product="item"/>
      </div>
    </main>

</template>

<script>
  
import ProductItem from '@/components/ProductItem.vue'

export default {
  name: 'MainComponent',
  props : {
    products: Array
  },
  components: {
    ProductItem
  }
}

</script>


<style scoped lang="scss">
main {
  background-color: black;
  color: white;
  line-height: 100px;
  vertical-align: middle;
  text-align: start;
}

.container {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
}


</style>
