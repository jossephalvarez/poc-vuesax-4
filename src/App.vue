<template>
  <div id="app">
    <HelloWorld msg=""/>
    <card-user/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import CardUser from './components/CardUser'

export default {
  name: 'App',
  components: {
    HelloWorld,
    CardUser
  }
}
</script>

<style>
  @import "https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
