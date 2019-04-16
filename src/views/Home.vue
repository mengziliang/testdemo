<template>
  <div class="home">
    <img alt="logo" src="../assets/logo.png" class="image1">
    <HelloWorld msg="icbcComponents"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped lang="stylus">
  .home
    .image1
      width 300px; margin 0 auto;
</style>
