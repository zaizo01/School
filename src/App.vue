<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import '@/assets/css/tailwind.css'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
</style>
