<template>
  <div id="app">
    <newTodo></newTodo>
  </div>
</template>

<script>
import Hello from './components/Hello'
import newTodo from './components/newTodo'

export default {
  name: 'app',
  components: {
    Hello,
    newTodo
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 20px;
}
</style>
