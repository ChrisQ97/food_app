<template>
  <div>
    <Greeting/>
    <Search/>
    <Featured/>
    <Scroll/>
    <Top/>
    <Barmenu/>
  </div>
</template>

<script>
import Barmenu from './components/Barmenu.vue';
import Greeting from './components/Greeting.vue';
import Search from './components/Search.vue';
import Featured from './components/Featured.vue';
import Scroll from './components/Scroll.vue';
import Top from './components/Top.vue';
export default {
  name: 'App',
  components: {
    Barmenu,
    Greeting,
    Search,
    Featured,
    Scroll,
    Top,
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
