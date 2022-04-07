<template>
  <div id="app">
    <Header />
    <Main :products="products"/>
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

//data
import products from '@/assets/data/dc-comics';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
  },
  data () {
    return {products}
  }

 
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
