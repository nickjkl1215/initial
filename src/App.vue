<template>
 <Primeiro curso="MEVN" :detalhes="true"/>
</template>

<script>
import Primeiro from './components/Primeiro'

export default {
  name: 'App',
  components: {
      Primeiro
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center; 
}
</style>
