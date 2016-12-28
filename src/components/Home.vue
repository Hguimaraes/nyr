<template>
  <div>
    <nav class="white">
      <div class="nav-wrapper">
        <a href="#" class="brand-logo center"></a>
      </div>
    </nav>
    <div class="container">
      <dashboard></dashboard>
    </div>
  </div>
</template>

<script>
import Dashboard from './Dashboard.vue'

export default {
  name: 'home',
  components: {
    Dashboard
  }
}
</script>

<style>

</style>