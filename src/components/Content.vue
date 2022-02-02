<template>
  <div class="content">
   <h1> --> Content goes here</h1>
  </div>
</template>

<script>
export default {
  name: 'Content',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.content{
  height: 120px;
  line-height: 120px;
  display: flex;
  align-items: center;
  background-color: #1C1C1C;
  h1{
    color: white;
    font-size: 25px;
  }
}
</style>
