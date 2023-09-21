<template>
  <div class="hello">
    <h1>你好，我是代佳妍 </h1>
    <p>学号:2310273125 | 手机/微信:13139371806 </p>
    <h1>{{ msg }}</h1>
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
<style scoped>

</style>