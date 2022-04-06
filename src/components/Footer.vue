<template>
  <footer>
    <div class="footer-top flex">
      <div class="col-2 flex footer-description">
        <img src="../assets/buy-comics-digital-comics.png" alt="Digital Comics">
        <p>DIGITAL COMICS</p>
      </div>
       <div class="col-2 flex footer-description">
        <img src="../assets/buy-comics-merchandise.png" alt="Dc Merhandise">
         <p>DC MERCHANDISE</p>
      </div>
      <div class="col-2 flex footer-description">
        <img src="../assets/buy-comics-subscriptions.png" alt="Subscription">
        <p>SUBSCRIPTION</p>
      </div>
       <div class="col-3 flex footer-description">
        <img src="../assets/buy-comics-shop-locator.png" alt="Comic Shop Locator">
         <p>COMIC SHOP LOCATOR</p>
      </div>
      <div class="col-3 flex footer-description">
        <img src="../assets/buy-dc-power-visa.svg" alt="Dc power visa">
         <p>DC POWER VISA</p>
      </div>
    </div>

    <div class="footer-middle flex">
        <div>
          <div class="flex-column ">
            <h3>DC COMICS</h3>
            <ul>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul> 
            <h3>SHOP</h3>
            <ul>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </div>
        </div>

        <div>
            <h3>DC</h3>
            <ul>
              <li><a href="#">Terms Of Use</a></li>
              <li><a href="#">Privacy policy (New)</a></li>
            </ul>   
        </div>

          <div>
            <h3>SITES</h3>
              <ul>
                 <li><a href="#">DC</a></li>
                 <li><a href="#">MAD Magazine</a></li>
                 <li><a href="#">DC Kids</a></li>
                 <li><a href="#">DC Universe</a></li>
                 <li><a href="#">DC Power Visa</a></li>
              </ul>
          </div>
     
      <img class="flex" src="../assets/dc-logo-bg.png" alt="">
    </div>

    <div class="footer-bottom flex">
        <button>SIGN-UP NOW</button>
        <div class="flex bottom-description">
          <a href="#">FOLLOW US</a>
          <div>
            <img src="../assets/footer-facebook.png" alt="Facebook">
            <img src="../assets/footer-twitter.png" alt="Twitter">
            <img src="../assets/footer-youtube.png" alt="Youtube">
            <img src="../assets/footer-pinterest.png" alt="Pinterest">
            <img src="../assets/footer-periscope.png" alt="Periscope">
          </div>
          
        </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterComponent',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.flex {
  display: flex;
}

h3 {
  color:white;
}

// footer top
.footer-top {
  height: 100px;
  background-color: #0282f9;
  justify-content: center;
}

.footer-top p {
  align-self: center;
  color: white;
}

.footer-top img {
  height: 50%;
   align-self: center;
   padding-right: 20px ;
}

.footer-description {
  margin-right: 40px;
}


//footer middle
.footer-middle {
  background-image: url("../assets/footer-bg.jpg");
  height: 400px;
  justify-content: space-around;
  text-align: start;
}

.footer-middle img {
  justify-self: end;
  size: cover;
}

.footer-middle ul {
  padding: 0;
}

.footer-middle li {
  list-style: none;
  margin-left: 0px;
}


.footer-middle a {
  color: white;
  text-decoration: none;

}



// footer-bottom
.footer-bottom {
  height: 100px;
  background-color: #303030;
  justify-content: space-around;
  line-height: 100px;
  vertical-align: middle;
}

.footer-bottom button {
  height: 60px;
  background-color: #303030;
  color: white;
  border: 1px solid #0282f9;
  margin-top: 20px;
}

.footer-bottom img {
  height: 30px;
  vertical-align: middle;
  padding-left: 10px;
}

.bottom-description {
  line-height: 100px;
  vertical-align: middle;
 
}

.bottom-description a {
  color: #037eec;
  text-decoration: none;
}

</style>
