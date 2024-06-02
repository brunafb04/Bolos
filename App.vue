<template>
  <img src="./assets/logo bolos.jpeg" alt="logo bolos" sizes="small">
  <HelloWorld msg="Marcia Bolos"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Times New Roman', Times, serif;
  font-size: larger;
  text-align: center;
  color: black;
  margin-top: 10px;
  background-color: lightblue;

}
</style>
