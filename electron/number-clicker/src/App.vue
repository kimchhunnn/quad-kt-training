<template>
  <NumberClicker/>
</template>

<script>
import NumberClicker from './components/NumberClicker.vue'

export default {
  name: 'App',
  components: {
    NumberClicker
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
  margin-top: 20%;
}
</style>
