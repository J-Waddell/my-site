<template>
  <img id="homeFace" alt="Vue logo" src="./assets/Jesse_Waddell.jpg">
  <HelloWorld msg="I'm here to punch ya baby"/>
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

#homeFace {
  width: 25%;
  border-radius: 3em;
}
</style>
