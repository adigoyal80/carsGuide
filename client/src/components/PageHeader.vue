<template>
  <div class="page-header">
    adventure<span>guide</span>
  </div>
</template>

<script>
export default {
  name: 'PageHeader',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.page-header{
  width: 100%;
  height: 48px;
  background: orange;
  color:white;
  span {
    color:black;
  }
}
</style>
