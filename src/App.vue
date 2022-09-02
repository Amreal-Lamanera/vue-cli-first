<template>
  <div id="app">
    <Title />
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Jumbo />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Title from './components/Title.vue'
import Jumbo from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    Title,
    Jumbo
  }
}
</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  // margin-top: 60px;
  padding: 0;
}
</style>
