<template>
  <div id="app" class="min-h-screen">
    <div class="flex flex-col md:flex-row md:justify-center">
    <header class="flex justify-center">
      <h1 class="text-5xl font-bold mt-10 tracking-wide text-center">Happy Eid <br> Mubarak</h1>
    </header>
    <section class="flex justify-center">
      <img src="./assets/raya.jpg" alt="raya.jpg">
    </section>
    <div class="flex justify-center">
      <button class="bg-green-300 rounded-lg py-2 px-4 shadow-md border border-gray-600 md:hidden">
        <a href="#">Duit Raya</a>
      </button>
    </div>
    </div>
    <footer class="flex justify-end md:hidden">
      <h1 class="px-3 font-semibold text-gray-800">@confirmnish</h1>
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
