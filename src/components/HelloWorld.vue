<template>
  <div class="hello">
      <div>这是master分支上</div>
      <div>我是在dev分支上</div>
      <div>这是master分支上第二次修改</div>
      <div>我是在dev分支上第二次修改了代码</div>
      <div>123</div>
      <p>hahaha</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
