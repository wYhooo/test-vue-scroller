<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <my-scroller></my-scroller>
  </div>
</template>

<script>
import MyScroller from './components/MyScroller'

export default {
  name: 'app',
  components: {
    MyScroller
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
