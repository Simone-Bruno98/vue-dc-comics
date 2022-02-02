<template>
  <div class="header">
    <img src="../assets/img/dc-logo.png" alt="">
    <ul>
      <li>
        characters
      </li>
      <li>
        comics
      </li>
      <li>
        movies
      </li>
      <li>
        tv
      </li>
      <li>
        games
      </li>
      <li>
        collectibles
      </li>
      <li>
        videos
      </li>
      <li>
        fans
      </li>
      <li>
        news
      </li>
      <li>
        shop
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header{
  height: 120px;
  line-height: 120px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  
  img{
    float: left;
    height: 80px;
    cursor: pointer;
  }
  ul{
    list-style-type: none;
    display: flex;
    justify-content: center;
    height: 120px;
    li{
      text-transform: uppercase;
      font-size: 12px;
      font-weight: 600;
      cursor: pointer;
      padding: 5px 10px;
      &:hover{
        color: #0282F9;
        border-bottom: 4px solid #0282F9;
      }
    }
  }
}
</style>
