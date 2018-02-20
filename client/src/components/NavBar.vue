<template>
  <nav id="navbar" class="navbar navbar-default navbar-inverse navbar-fixed-top" role="navigation">
        <div class="container">
            <div class="navbar-header">
              <h2>adventure<span>guide</span></h2>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
  name: 'NavBar',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

#navbar {
  background: #ffb54c;
  height: 48px;
  font-family: Arial Black;
  margin-bottom:53px;
}

.navbar-header {
  color:white;
  h2{
    position: relative;
    right: 20px;
  }
}

.navbar-header span {
  color:black;
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
