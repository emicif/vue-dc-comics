<template>
  <header class="flex">
    <img class="logo" src="../assets/dc-logo.png" alt="Dc Logo"/>
    <nav class="menu">
      <li><a href="#"> CHARACTERS </a></li>
      <li><a href="#"> COMICS </a></li>
      <li><a href="#"> MOVIES </a></li>
      <li><a href="#"> TV </a></li>
      <li><a href="#"> GAMES </a></li>
      <li><a href="#"> COLLECTIBLES </a></li>
      <li><a href="#"> VIDEOS </a></li>
      <li><a href="#"> FANS </a></li>
      <li><a href="#"> NEWS </a></li>
      <li><a href="#"> SHOP </a></li>
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
