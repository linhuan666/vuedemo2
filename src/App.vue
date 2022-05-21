<template>
  <div id="app">
    <div class="header">
      <input type="text">{{msg}}
    </div>
    <Swiper :list="list"></Swiper>

  </div>
</template>


<script>
//import HelloWorld from './components/HelloWorld.vue'
import  Swiper from './components/Swiper'

export default {
  name: 'App',
  components: {
    // eslint-disable-next-line vue/no-unused-components
     Swiper
  },
  data(){
    return{
      msg:"我是vue",
      list:[1,2,3,4]
    }
  }
}
</script>

<style scoped>
#app {
 background-color: red;
  overflow: hidden;
}
#app .header{
  margin-top: 30px;
}
</style>
