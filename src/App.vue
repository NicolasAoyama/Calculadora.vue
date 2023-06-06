<template>
  <ComponentCalculadora msg="Calculador Vue"/>
</template>

<script>
import ComponentCalculadora from './components/ComponentCalculadora.vue';

export default {
  name: 'App',
  components: {
    ComponentCalculadora
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
