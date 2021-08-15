<template>
  <div>
    <Greeting/>
    <Search/>
    <Barmenu/>
  </div>
</template>

<script>
import Barmenu from './components/Barmenu.vue';
import Greeting from './components/Greeting.vue';
import Search from './components/Search.vue';
export default {
  name: 'App',
  components: {
    Barmenu,
    Greeting,
    Search,
  }
}
</script>

<style lang="less">

#app {

  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
* {
  font-family: 'Raleway', sans-serif;
  margin: 0px;
  padding: 0px;
 }
</style>
