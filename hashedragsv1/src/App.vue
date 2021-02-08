<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <app-header></app-header>
    <HelloWorld msg="Welcome to Your Vue.js"/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import HelloWorld from './components/HelloWorld.vue';

export default {
  components: {
    AppHeader,
    HelloWorld
  }
};

</script>

<style>

</style>
