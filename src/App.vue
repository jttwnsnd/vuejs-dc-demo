<template>
  <div id="app">
    <div class="row">
      <div class="col-xs-12">
        <h1>Vue.js <strong>Discovery</strong></h1>
        <h5>{{ message }}</h5>
      </div>
    </div>
    <div class="row">
      <div class="col-xs-12">
        <h2>Directives</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-xs-12">
        <h2>Methods</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to the Vue.js Demo'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

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

strong {
  color: #42b983;
}
</style>
