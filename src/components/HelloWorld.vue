<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Installed CLI Plugins</h3>
    <h1>你好 我是中国人</h1>

    <h1>全新的分支(r4bj0) 人为制造冲突 然后合并冲突</h1>
    <h2>创建一个全新的分支pp242 并且合并到主分支</h2>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
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
