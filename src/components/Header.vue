<template>
  <header class="flex">
    <img class="logo" src="../assets/dc-logo.png" alt="Dc Logo"/>
    <nav class="menu flex">
      <ul>
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
      </ul>
      
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
  height: 100px;
  margin: 10px auto;
  justify-content: space-around;
}

nav {
  vertical-align: middle;
}

ul {
  list-style: none;
  vertical-align: middle;
  line-height: 100px;
}


nav li {
  display: inline-block;
  list-style-type: none;
  padding-left: 10px;
  
}

nav a {
  text-decoration: none;
  color: grey;

}

nav li a:hover {
  color: #0282f9;
}



nav a {
  position: relative;
  padding: 30px 20px;
}

a::after {
  content: ' ';
  position: absolute;
  left: 0;
  bottom: -5px;
  width: 100%;
  height: 0;
  background: #0282f9;
}


a:hover::after {
  height: 5px;
}

</style>
