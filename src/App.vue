<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/1.gif">
    <HelloWorld msg="命运有随造化安排，也与个人的性格关系极大。应该说，往往是自己决定了做奴才，才终于做稳了奴才，把吆喝当赞歌，人乞祭余，甘之如饴。"/>
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
