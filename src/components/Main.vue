<template>
  <div class="hello">
    <main>
      <!-- striscia nera -->
      <div class="text">--> Content goes here --></div>
    </main>
    
  </div>
</template>

<script>
export default {
  name: 'MainComponent',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
main {
  height: 100px;
  background-color: black;
  color: white;
  line-height: 100px;
  vertical-align: middle;
  text-align: start;
}

.text {
    width: 80%;
    height: 100px;
    margin: 10px auto;
}
</style>
