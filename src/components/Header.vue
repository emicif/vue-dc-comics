<template>
  <header class="flex">
    <img class="logo" src="../assets/dc-logo.png" alt="Dc Logo"/>
    <nav class="menu">
      <a href="#"> CHARACTERS </a>
      <a href="#"> COMICS </a>
      <a href="#"> MOVIES </a>
      <a href="#"> TV </a>
      <a href="#"> GAMES </a>
      <a href="#"> COLLECTIBLES </a>
      <a href="#"> VIDEOS </a>
      <a href="#"> FANS </a>
      <a href="#"> NEWS </a>
      <a href="#"> SHOP </a>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComponent',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.flex {
  display: flex;
}

header {
  width: 80%;
  height: 50px;
  margin: 10px auto;
  justify-content: space-around;
}

nav {
  line-height: 50px;
  vertical-align: middle;
}

nav a {
  text-decoration: none;
  color: grey;
}
</style>
