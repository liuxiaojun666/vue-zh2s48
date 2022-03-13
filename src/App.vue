<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    {{ dayjs(0) }}
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import dayjs from 'dayjs';

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      dayjs
    }
  },
  mouted () {

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
