<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h1>姓名：刘旭</h1>
  <h1>学号：2310275003</h1>
  <img alt="pika" src="./assets/pika.jpg">
  <HelloWorld msg="Welcome to Your Vue.js App"/>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
