<template>
  <div id="app">
    <Header/>
    <Content/>
    <Nav/>
    <Footer1/>
    <Footer2/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Content from './components/Content.vue'
import Nav from './components/Nav.vue'
import Footer1 from './components/Footer1.vue'
import Footer2 from './components/Footer2.vue'

export default {
  name: 'App',
  components: {
    Header,
    Content,
    Nav,
    Footer1,
    Footer2,
  }
}

</script>

<style lang="scss">
@import './assets/style/general.scss';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
