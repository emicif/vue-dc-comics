<template>
    <main>
      <button class="button-current"><strong>CURRENT SERIES</strong></button>
      <div class="container">
       
        <ProductItem v-for="(item, index) in products" :key="index" :product="item"/>
        <div class="button-load"><button><strong>LOAD MORE</strong></button></div>
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
  background-color: #1c1c1c;
  position: relative;
  .button-current {
    position: absolute;
    top: -10px;
    left: 400px;
    background-color: #0282f9;
    color: white;
    padding: 15px;
    border: none;
    font-size: 1.5rem;
    cursor: pointer;
  }
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
   button {
    background-color: #0282f9;
    color: white;
    padding: 10px;
    border: none;
    margin-bottom: 10px;
    cursor: pointer;
  }
  .button-load {
    width: 100%;
  }
}


</style>
