<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <div id="app">
    <h1>To-Do List</h1>
    <ul>
    <li>
      <to-do-item label="My To Do Item" :done="true"></to-do-item>
    </li>
  </ul>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import ToDoItem from "./components/ToDoItem.vue";



export default {
  name: 'App',
  components: {
    ToDoItem
  //   HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Calibri, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0a0a0a;
  margin-top: 60px;
}
</style>
