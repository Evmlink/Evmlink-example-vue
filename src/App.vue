<template>
  <Home />
  <ConnectWallte/>

</template>
<script>
import ConnectWallte from './components/ConnectWallteExample.vue';
import Home from "./Home.vue"
export default {
    components: {
        ConnectWallte,
        Home
  },
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
