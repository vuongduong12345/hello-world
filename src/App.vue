<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Test2 title="a123456"/>
    <Lifecycle hihi="gggggg"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Test2 from './components/test2'
import Lifecycle from './components/Lifecycle'
export default {
  name: 'app',
  components: {
    // HelloWorld,
    Test2,
    Lifecycle
      }
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
