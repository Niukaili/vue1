<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>在dev分支上</p>
    <h4>master代码</h4>

    <h2>dev分支</h2>
    <div>111111111</div>
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
