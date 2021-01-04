<template>
  <div id="app">
    <h2> Number Clicker </h2>
    <button v-on:click="number -= 1">-</button>
    <h3> {{ number }} </h3>
    <button v-on:click="number += 1">+</button>
  </div>
</template>

<script>
export default {
  name: 'NumberClicker',
  data: function () {
    return {
      number: 0
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
button {
  padding: 10px 20px;
  border: 1px solid #008CBA;
  color: #ffffff;
  background-color: #008CBA;
  border-radius: 4px;
  font-size: 14px;
  font-family: '微软雅黑',arail;
  cursor: pointer;
}
h3 {
  padding: 10px 30px;
  display: inline;
}
</style>
