<template>
  <div id="app">
    <h1>{{ msg }}</h1>
    
    <!----- Demo 1. Insert The component name, as shown below -->
    <todo-card></todo-card>
    <aboutus></aboutus> 
  </div>
</template>

<script>
//import the newly created components
import TodoCard from './components/TodoCard'
import AboutUs from './components/AboutUs'

export default {
  components: { TodoCard },
  name: 'app',
  components : {
    TodoCard,
    AboutUs
  },
  data () {
    return {
      msg: 'The Main Components'
    }
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