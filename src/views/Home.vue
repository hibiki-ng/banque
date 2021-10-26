<template>
  <div class="flex h-screen font-sans home">
    <Navbar/>
    <div class="flex flex-col justify-around mt-10 ml-10 w-4/5 h-5/6 rounded-lg p-5 bg-gradient-to-br from-blue-100 to-blue-200">
      <div id="cardlist1" class="flex flex-row justify-around">
        <div class="flex flex-col w-1/3 h-60 p-4 rounded-lg bg-gradient-to-br from-blue-400 to-blue-500 text-white pointer" onclick="location.href='d:/wamp/banque/operations.html'">
          <h2 class=" text-4xl font-medium">Solde</h2>
          <div class="flex self-center justify-self-center h-20 mt-7">
            <h3 class="justify-self-center self-center text-5xl">1224.96€</h3>
          </div>
        </div>
        <div class="flex flex-col w-2/4 h-80 p-4 rounded-lg bg-gradient-to-br from-blue-400 to-blue-500 text-white pointer" onclick="location.href='d:/wamp/banque/operations.html'">
          <div class="flex flex-row justify-between">
            <h2 class="text-4xl font-medium">Transactions</h2>
            <h3 class="pr-4 pt-3 text-xl">Septembre 2021</h3>
          </div>
          <div id="transactions" class="flex flex-row h-60 mt-6 py-5 px-16 text-3xl font-medium">
            <div class="flex flex-col w-1/3 leading-relaxed">
              <h3>Spotify</h3>
              <h3>Microsoft</h3>
              <h3>Amazon</h3>
            </div>
            <div class="flex flex-col w-1/3 leading-relaxed">
              <h3>15/09</h3>
              <h3>13/09</h3>
              <h3>08/09</h3>
            </div>
            <div class="flex flex-col w-1/3 leading-relaxed">
              <h3>14.99€</h3>
              <h3>13.99€</h3>
              <h3>73.85€</h3>
            </div>
          </div>
          <div class="px-8">
            <a href="">Voir toutes les transactions →</a>
          </div>
        </div>
      </div>
      <div id="cardlist2" class="flex flex-row justify-around ml-10 text-white font-medium">
        <div class="flex flex-col w-1/4 h-60 p-5 rounded-lg bg-gradient-to-br from-indigo-400 to-indigo-500 pointer" onclick="location.href='d:/wamp/banque/operations.html'">
          <h2 class="text-4xl">Entrées</h2>
          <div class="flex self-center justify-self-center h-20 mt-10">
            <h3 class="justify-self-center self-center text-3xl">1238.21€</h3>
          </div>
        </div>
        <div class="flex flex-col w-1/4 h-60 p-5 rounded-lg bg-gradient-to-br from-indigo-400 to-indigo-500 pointer" onclick="location.href='d:/wamp/banque/operations.html'">
          <h2 class="text-4xl">Dépenses</h2>
          <div class="flex self-center justify-self-center h-20 mt-10">
            <h3 class="justify-self-center self-center text-3xl">-348.67€</h3>
          </div>
        </div>
        <div class="flex flex-col w-2/6 h-6P p-5 rounded-lg bg-gradient-to-br from-indigo-400 to-indigo-500 pointer" onclick="location.href='d:/wamp/banque/operations.html'">
          <h2 class="text-4xl">Comparaison budget</h2>
          <div class="flex self-center justify-self-center h-20 mt-10">
            <h3 class="justify-self-center self-center text-3xl">à faire</h3>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Home',
  components: {
    Navbar
  }
}
</script>
