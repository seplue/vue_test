<template>
  <div id="app">
    <!--
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MyFirstComponent></MyFirstComponent>
    <TodoItem>

    </TodoItem>
    -->
    <AxiosTest>

    </AxiosTest>
  </div>
</template>

<script>

import AxiosTest from "@/components/AxiosTest";

export default {
  name: 'app',
  components: {
    AxiosTest
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
