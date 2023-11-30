<template>
  <IndecisionComponents/>
</template>

<script>
import IndecisionComponents from './components/IndecisionComponents.vue'

// import CounterComponent from './components/CounterComponent'

   

export default {
  name: 'App',
  components: {
    IndecisionComponents,
  // CounterComponent,
  
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
