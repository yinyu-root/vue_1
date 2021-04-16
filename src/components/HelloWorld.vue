<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For baidu,<br>
      check out the
      <a href="https://baidu.com" target="_blank" rel="noopener">baidu</a>.
    </p>
    <h2>for baidu</h2>
    <ul>
      <li><a href="https://baidu.com" target="_blank" rel="noopener">baidu</a></li>
      <li><a href="https://baidu.com" target="_blank" rel="noopener">baidu</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Hello',
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
