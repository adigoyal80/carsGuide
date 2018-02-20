<template>
  <section class="row">
        <ol class="breadcrumb col-sm-9">
          <li class="breadcrumb-item">
            <a class="crumb-link" href="#">Nissan</a>
            </li>
          <li class="breadcrumb-item">
            <a class="crumb-link" href="#">Pathfinder</a>
            </li>
          <li class="breadcrumb-item">
            <a class="crumb-link" href="#">Reviews</a>
            </li>
          <li class="breadcrumb-item">
            <a class="crumb-link" href="#">Current</a>
            </li>
        </ol>
    </section>
</template>

<script>
export default {
  name: 'BreadCrumbs',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

.breadcrumb-item {
  font-size: 0.8em;
}
</style>
