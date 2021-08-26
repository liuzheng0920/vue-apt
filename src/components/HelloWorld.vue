<template>
  <div id="header">
    <h1>hello</h1>
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

<style scoped lang="less">
@width: 10px;
@height: @width + 10px;
#header {
  width: @width;
  height: @height;
}
</style>
