<template>
  <div id="app">
  	<navbar></navbar>
  	<main>
  		<dashboard></dashboard>
  		<arts></arts>
  		<books></books>
  		<education></education>
  		<experience></experience>
  		<fitness></fitness>
  		<others></others>
  	</main>
  </div>
</template>

<script>
import Navbar from './components/commons/navbar.vue'
import Dashboard from './components/Dashboard.vue'
import Arts from './components/Arts.vue'
import Books from './components/Books.vue'
import Education from './components/Education.vue'
import Experience from './components/Experience.vue'
import Fitness from './components/Fitness.vue'
import Others from './components/Others.vue'

export default {
  name: 'app',
  components: {
    Navbar, Dashboard, Arts, Books, Education, Experience, Fitness, Others
  }
}
</script>

<style>
</style>
