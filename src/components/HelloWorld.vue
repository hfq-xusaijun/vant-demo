<template>
  <div>
      <van-loading color="black" />
      <!-- <van-loading color="white" /> -->
      <van-loading type="spinner" color="black" />
      <van-loading type="spinner" color="greenyellow" />
  </div>
</template>

<script>
import { Loading } from 'vant'
export default {
  name: 'HelloWorld',
  components: {
    [Loading.name]: Loading
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
