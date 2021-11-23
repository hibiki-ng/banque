<template>
  <div class="flex h-screen font-sans home">
    <Navbar/>
    <div>
      <h1>test</h1>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Operations',
  components: {
    Navbar
  }
}
</script>
