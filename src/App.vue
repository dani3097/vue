<template>
  <div id="app">
    <img src="https://www.herbmusic.net/artist/photo/2017/05/351-coldplay.jpg">
    <Music/>
  </div>
</template>

<script>
import Music from './components/Music'
export default {
  name: 'App',
  components: {
    Music
  }
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0c0c0c;
  margin-top: 60px;
}
</style>
