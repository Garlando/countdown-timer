<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <timer-input msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import TimerInput from './components/TimerInput.vue'

export default {
  name: 'App',
  components: {
    TimerInput
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
  background-color: aqua;
}
</style>
