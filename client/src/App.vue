<template>
  <div id="app">
    <PageHeader/>
    <img src="./assets/logo.png">
    <Container/>
  </div>
</template>

<script>
import Container from './components/Container'
import PageHeader from './components/PageHeader'

export default {
  name: 'App',
  components: {
    Container,
    PageHeader
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
}

body {
  margin: 0;
  padding: 0;
}

</style>
