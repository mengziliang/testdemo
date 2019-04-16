<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <input type="button" value="掃一掃">
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
  .hello
    h1
      color red;
</style>
