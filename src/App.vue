<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <anchored-heading :level="1">heading one</anchored-heading>
    <router-view/>
  </div>
</template>

<script>
import AnchoredHeading from './components/anchored-heading'
export default {
  name: 'App',
  data(){
    return {};
  },
  components: {
    AnchoredHeading
  },
  props: {

  },
  methods: {

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
