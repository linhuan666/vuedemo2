<template>
  <div>
    <ul>
      <li v-for="item in list">{{item}}</li>
    </ul>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Swiper",
  props:{
    list:Array
  }
}
</script>

<style scoped>

</style>