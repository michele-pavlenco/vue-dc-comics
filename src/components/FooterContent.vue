<template>
  <footer>
    <section class="section1">
      <div class="container">
        <div class="footer-first">
          <div class="immage">
            <img
              src="../assets/immagini/buy-comics-digital-comics.png"
              alt=" Digital comix"
            />
            <p>Digital comix</p>
          </div>
          <div class="immage">
            <img
              src="../assets/immagini/buy-comics-merchandise.png"
              alt="DC Merchandise"
            />
            <p>DC Merchandise</p>
          </div>
          <div class="immage">
            <img
              src="../assets/immagini/buy-comics-subscriptions.png"
              alt="Subscriptions"
            />
            <p>Subscriptions</p>
          </div>
          <div class="immage">
            <img
              src="../assets/immagini/buy-comics-shop-locator.png"
              alt="Comic shop locator"
            />
            <p>Comic shop locator</p>
          </div>
          <div class="immage">
            <img
              class="visa"
              src="../assets/immagini/buy-dc-power-visa.svg"
              alt="DC power visa"
            />
            <p>DC power visa</p>
          </div>
        </div>
      </div>
    </section>

    <section class="section2">
      <div class="container">
        <div class="footer-second">
          <div class="list-group">
            <div class="list-group1">
              <ul>
                <li>DC Comics</li>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
              </ul>
              <ul>
                <li>Shop</li>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
              </ul>
            </div>
            <div class="list-group2">
              <ul>
                <li>DC</li>
                <li>Terms Of Use</li>
                <li>Privacy policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop help</li>
                <li>Contact us</li>
              </ul>
            </div>
            <div class="list-group3">
              <ul>
                <li>Sites</li>
                <li>DC</li>
                <li>Mad magazine</li>
                <li>DC kids</li>
                <li>DC universe</li>
                <li>DC power visa</li>
              </ul>
            </div>
          </div>
          <div class="list-group-image">
            <img src="../assets/immagini/dc-logo-bg.png" alt="" />
          </div>
        </div>
      </div>
    
    <section class="section3">
      <div class="container">
        <div class="footer-third">
          <button>Sing-up now!</button>
          <ul>
            <li>Follow us</li>
            <li><img src="../assets/immagini/footer-facebook.png" alt="" /></li>
            <li><img src="../assets/immagini/footer-twitter.png" alt="" /></li>
            <li><img src="../assets/immagini/footer-youtube.png" alt="" /></li>
            <li>
              <img src="../assets/immagini/footer-pinterest.png" alt="" />
            </li>
            <li>
              <img src="../assets/immagini/footer-periscope.png" alt="" />
            </li>
          </ul>
        </div>
      </div>
    </section>
    </section>
  </footer>
</template>
<script>
export default {
  name: "FooterContent",
};
</script>

<style scoped>
.section1 {
  background-color: #0c7cec;
}

.footer-first {
  display: flex;
  height: 130px;
  justify-content: space-around;
  align-items: center;
}
.footer-first .immage {
  display: flex;
  align-items: center;
  color: white;
  padding: 5px;
}
.footer-first .immage p {
  padding: 8px;
  text-transform: uppercase;
  font-size: 13px;
}
.footer-first img {
  height: 40px;
  background-size: contain;
}
.footer-first .visa {
  height: 30px;
}
.section2 {
  background-image: url(../assets/immagini/footer-bg.jpg);
  background-size: cover;
  height: 350px;
}
.footer-second {
  display: flex;
  justify-content: space-between;
}
.list-group {
  display: flex;
  color: white;
  height: 300px;
}
.list-group li:first-child {
  font-weight: bold;
  padding-bottom: 10px;
  font-size: 17px;
  color: white;
}
.list-group li {
  list-style-type: none;
  font-size: 14px;
  color: rgb(160, 160, 160);
}
.list-group-image {
  width: 50%;
  overflow:hidden;
}
.list-group-image img{
  background-size: contain;
  height: 440px;
  margin-top: -10%;
  margin-bottom: -10%;
  float: right;
}
.section3 {
  background-color: #303030;
}
.footer-third {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 80px;
}
.footer-third li {
  display: inline;
  vertical-align: middle;
  margin: 7px;
  color: #0c7cec;
  font-weight: bold;
  text-transform: uppercase;
}
.footer-third button {
  background-color: #303030;
  height: 35px;
  border: 2px solid #0c7cec;
  text-transform: uppercase;
  color: white;
}
</style>
