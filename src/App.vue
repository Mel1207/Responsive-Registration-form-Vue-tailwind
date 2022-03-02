<template>
  <Navbar />
  <Home />
  <About />
</template>

<script>
import Navbar from './components/Navbar.vue'
import Home from './views/HomeView.vue'
import About from './views/AboutView.vue'

export default {
  components: { Navbar, Home, About }
}

</script>
