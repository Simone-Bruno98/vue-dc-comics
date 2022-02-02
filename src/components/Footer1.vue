<template>
  <div class="footer1">
    <div class="lista">
      <ul>
        <li><h1>dc comics</h1></li>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Videos</li>
        <li>News</li>
        <li><h1>shop</h1></li>
        <li>Shop DC</li>
        <li>Shop DC Collectibles</li>
      </ul>
      <ul>
        <li><h1>dc</h1></li>
        <li>Terms Of Use</li>
        <li>Privacy policy (New)</li>
        <li>Ad Choices</li>
        <li>Advertising</li>
        <li>Jobs</li>
        <li>Subscriptions</li>
        <li>Talent Workshops</li>
        <li>CPSC Certificates</li>
        <li>Ratings</li>
        <li>Shop Help</li>
          <li>Contact Us</li>
      </ul>
      <ul>
        <li><h1>sites</h1></li>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>
      </ul>
    </div>
    <div class="immagine">
      <img src="../assets/img/dc-logo-bg.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer1',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.footer1{
  height: 400px;
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  justify-content: space-between;
  .lista{
    display: flex;
    ul{
    list-style-type: none;
      li{
        font-size: 15px;
        color: gray;
        h1{
          font-size: 25px;
          text-transform: uppercase;
          color: white;
          margin: 20px 0px;
        }
        margin: 10px 0px;
        text-align: left;
      }
    }
  }
  .immagine{
    height: 100%;
    overflow: hidden;
    display: flex;
    img{
      height: 450px;
      align-self: center;
    }
  }
  
}
</style>
