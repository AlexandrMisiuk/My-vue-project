<template>
<div class="wrap">
  <div class="images">
    <img alt="Vue logo" src="./assets/logo.png">
    <img alt="My Foto" src="./assets/IMG_20180719_213519_384.jpg">
  </div>
  <Block msg="Welcome to My project Vue.js"/>
  <Footer />
</div>
</template>

<script>
import Block from './components/Block.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Block,
    Footer
  }
}
</script>

<style>
*{
  box-sizing: border-box;
}
body{
  margin: 0;
  padding: 0;
  background-color: #2c3e50;
}
.wrap {
  max-width: 1000px;
  min-width: 800px;
  margin: 0 auto;
  min-height: 100vh;
  height: auto;
  padding-top: 3vh;
  display: flex;
  flex-flow: column nowrap;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #e2e2e2;
}
.images{
  display: flex;
  justify-content: space-evenly;
}
.images img{
  width: 200px;
  height: 200px; 
  object-fit: contain;
}
.images img:last-of-type{
  border-radius: 50%;
}
</style>
