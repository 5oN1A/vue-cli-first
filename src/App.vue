<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
     <Title msg="Mio componente"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Title from './components/Title.vue';

export default {
  name: 'App',
  data(){
    return {
     
    }
  },
  components: {
    HelloWorld, 
    Title
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
