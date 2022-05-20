<template>
  <div id="app">
    <div class="header">
      <input type="text">{{msg}}

    </div>

  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {

  },
  data(){
    return{
      msg:"我是vue"
    }
  }
}
</script>

<style scoped>
#app {
 background-color: red;
}
</style>
