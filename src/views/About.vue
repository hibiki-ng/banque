<template>
  <div class="flex h-screen font-sans home">
    <Navbar/>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'About',
  components: {
    Navbar
  }
}
</script>
