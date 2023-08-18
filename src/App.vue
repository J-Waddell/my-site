<template>
  <div class="img-container">
    <img id="homeFace" alt="Vue logo" src="./assets/Jesse_Waddell.jpg">
  </div>
  <HelloWorld msg="Jesse M. Waddell"/>
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

.img-container {
  background-color: black;
  width: 100%;
}

#homeFace {
  width: 25%;
  border-radius: 3em;
}
</style>