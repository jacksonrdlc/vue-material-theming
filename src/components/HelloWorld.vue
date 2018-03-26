<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <div>
      <md-toolbar>
        <h3 class="md-title">Default</h3>
      </md-toolbar>
  
      <md-toolbar md-elevation="0">
        <h3 class="md-title">No Elevation</h3>
      </md-toolbar>
  
      <md-toolbar class="md-transparent">
        <h3 class="md-title">Transparent</h3>
      </md-toolbar>
  
      <md-toolbar class="md-primary">
        <h3 class="md-title">Primary</h3>
      </md-toolbar>
  
      <md-toolbar class="md-accent">
        <h3 class="md-title">Accent</h3>
      </md-toolbar>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1,
  h2 {
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
