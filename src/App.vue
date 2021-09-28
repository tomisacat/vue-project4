<template>
  <div id="app">
    <img alt="Vue logo" src="http://wx2.sinaimg.cn/mw1024/007QHGQRly1guqxxo6dt6g607s08g1kz02.gif">
    <HelloWorld msg="狗东西们，Morning Call 了吗"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
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
