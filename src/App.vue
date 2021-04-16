<!--展示模板-->
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/zcm.jpg">
    <Helloa msg="Welcome to My Home"/>
  </div>
</template>

<script>
//导入组件
//import HelloWorld from './components/HelloWorld.vue'
import Helloa from "@/components/HelloWorld";

export default {
  name: 'App',
  components: {
    Helloa
  }

}
</script>

<!--样式代码-->
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
