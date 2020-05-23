<template>
  <div id="app" class="min-h-screen">
    <div class="flex flex-col md:flex-row md:justify-between">
    <header class="flex justify-center md:flex-col md:pl-40">
      <h1 class="text-5xl font-bold mt-10 tracking-wide text-center md:pl-16">Happy Eid <br> Mubarak</h1>
      <button class="bg-green-300 py-2 shadow-lg border border-gray-800 rounded-lg md:flex-shrink hidden">Duit Raya</button>
    </header>
    <section class="flex justify-center">
      <img class="md:pr-10" src="./assets/raya.jpg" alt="raya.jpg">
    </section>
    <div class="flex justify-center md:hidden">

    </div>
    </div>
    <footer class="w-full text-center pt-10 pin-b">
      <h1 class="px-3 font-bold text-gray-800">@Danish Ikhwan</h1>
    </footer>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style src="./css/tailwind.css">
</style>
<style>
  #app{
    background-color: #E1EFBE;
  }
</style>
