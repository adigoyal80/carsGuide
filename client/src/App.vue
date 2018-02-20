<template>
  <div id="app">
    <nav-bar></nav-bar>
    
    <container></container>
  </div>
</template>

<script>
import Container from './components/Container'
import NavBar from './components/NavBar'

export default {
  name: 'app',
  components: {
    Container,
    NavBar
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;


//breadcrumbs
  .breadcrumb {
    background: none;
    
    margin: 0;

    .breadcrumb-item {
      font-style: italic;

      &+.breadcrumb-item::before {
        content: '>';
      }

      .crumb-link {
        color:black;
      }
    }
  }
  



}
</style>
