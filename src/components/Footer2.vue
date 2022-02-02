<template>
  <div class="footer2">
    <div class="signupbutton">
      <span>sign-up now!</span>
    </div>
    <div class="rightnav">
      <span>follow us</span>
      <img src="../assets/img/footer-facebook.png" alt="">
      <img src="../assets/img/footer-twitter.png" alt="">
      <img src="../assets/img/footer-youtube.png" alt="">
      <img src="../assets/img/footer-pinterest.png" alt="">
      <img src="../assets/img/footer-periscope.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer2',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .footer2{
    height: 140px;
    background-color: #303030;
    display: flex;
    justify-content: space-between;
    align-items: center;
    .signupbutton{
      color: #0282F9;
      text-transform: uppercase;
      border: 3px solid #0282F9;
      padding: 10px 10px;
    }
    .rightnav{
      span{
        text-transform: uppercase;
        color: #0282F9;
        padding: 0px 10px;
      }
      img{
        padding: 0px 10px;
        height: 40px;
        vertical-align: middle;
        color:#797979;
      }
    }
  }
</style>
