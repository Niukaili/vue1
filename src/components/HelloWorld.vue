<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>主分支</h3>
    <p>马旭东分支</p>
    <h3>克隆代码</h3>
    <p>我是远程操控的马旭东000000000000</p>
    <p>牛凯莉贼眉鼠眼</p>
    <h4>吉杰贼眉鼠眼</h4>
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
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
