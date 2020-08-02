<template>
  <div id="app">
    <MyName name="Wahab Giwa"/>
  </div>
</template>

<script>
import MyName from './components/MyName.vue'

export default {
  name: 'App',
  components: {
    MyName
  }
}
</script>

<style>
* {
  padding: 0;
  border: 0;
  margin: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ebebeb;
  background-color: black;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  /* margin-top: 60px; */
}
</style>
