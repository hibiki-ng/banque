<template>
  <div class="hello">
    <div id="navbar" class="flex flex-col pl-2 w-60 h-5/6 ml-8 mt-10 justify-between rounded-lg">
      <div class="">
        <a href="index.html" class="font-mono text-3xl font-bold mt-4">Banque</a>
      </div>
      <div class="flex flex-col justify-around h-60">
        <a href="#">Opérations</a>
        <a href="#">Budget</a>
        <a href="#">Virement</a>
        <a href="#">Mode sombre</a>
      </div>
      <div class="flex flex-col h-60 leading-loose justify-end">
        <a href="#">S'inscrire</a>
        <a href="#">Se connecter</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
