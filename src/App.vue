<template>
  <div id="app">
    <!--
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MyFirstComponent></MyFirstComponent>
    <TodoItem>

    </TodoItem>

    <AxiosTest>

    </AxiosTest>
    -->
    <AxiosBitcoin>

    </AxiosBitcoin>
  </div>
</template>

<script>

import AxiosTest from "@/components/AxiosTest";
import AxiosBitcoin from "@/components/AxiosBitcoin";

export default {
  name: 'app',
  components: {
    AxiosBitcoin,
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
