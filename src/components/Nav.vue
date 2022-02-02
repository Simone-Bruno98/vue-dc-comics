<template>
  <div class="nav">
    <div class="element">
      <img src="../assets/img/buy-comics-digital-comics.png" alt="">
      <span>digital comics</span>
    </div>
    <div class="element">
      <img src="../assets/img/buy-comics-merchandise.png" alt="">
      <span>dc merchandise</span>
    </div>
    <div class="element">
      <img src="../assets/img/buy-comics-subscriptions.png" alt="">
      <span>subscription</span>
    </div>
    <div class="element">
      <img src="../assets/img/buy-comics-shop-locator.png" alt="">
      <span>comic shop locator</span>
    </div>
    <div class="element">
      <img src="../assets/img/buy-dc-power-visa.svg" alt="">
      <span>dc power visa</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Nav',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.nav{
  height: 140px;
  line-height: calc(140px - 30px);
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  background-color: #0282F9;
  color: white;
  .element{
    img{
      height: 60px;
      vertical-align: middle;
    }
    span{
      text-transform: uppercase;
      padding: 0px 10px;
    }
  }
}
</style>
