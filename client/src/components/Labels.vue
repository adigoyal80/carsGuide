<template>
  <section class="row">
    <div class="label-container col-sm-9">
      <b-badge class="label">
        <a class="label-link" href="#">Pathfinder</a>
      </b-badge>
      <b-badge class="label">
        <a class="label-link" href="#">Nissan</a>
      </b-badge>
      <b-badge class="label">
        <a class="label-link" href="#">SUV</a>
      </b-badge>
      <b-badge class="label">
        <a class="label-link" href="#">Nissan SUV Range</a>
      </b-badge>
      <b-badge class="label">
        <a class="label-link" href="#">Family Range</a>
      </b-badge>
      <b-badge class="label">
        <a class="label-link" href="#">7 Seater</a>
      </b-badge>      
    </div>
  </section>
</template>

<script>
export default {
  name: 'Labels',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.label-link {
  color: black;
}

.row{
  padding-bottom: 1rem;
}

.badge {
  border-radius: 1rem;
  background: #e8e8e8;
}
</style>
