<template>
  <div id="app">
  <div class="test" @click='test'></div>
    <router-view/>
  </div>
</template>

<script>
import './css/styles.scss'
export default {
  name: 'app',
  methods:{
    test(){
      console.log('test')
    },
  },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: red;
  margin-top: 60px;
}
</style>
