<template>
  <div
    class="container relative min-h-screen flex mx-auto md:flex-row flex-col items-center justify-between"
  >
    <div class="flex flex-wrap">
      <div>
        <h2 class="text-gray-800 font-semibold text-5xl prose prose-md">
          Welcome Dashboard!
        </h2>
        <p class="text-lg pt-6 text-gray-600 font-bold">
          The Great Asia Africa,
          <span class="text-red-700 font-semibold">Lembang</span>
        </p>
        <p class="pb-6 text-gray-600">
          Taman bertema khusus Afrika dan Asia dengan replika desa, <br />kebun
          binatang kecil, makanan, dan suvenir.
        </p>
        <button
          class="bg-red-600 hover:bg-red-500 text-white font-bold py-2 px-4 rounded-full"
        >
          Get Started
        </button>
      </div>
    </div>
    <div class="absolute left-2/4 pt-28">
      <img
        class="object-cover h-82 w-96 rounded"
        alt="hero"
        src="../assets/img/6.jpg"
      />
    </div>
    <div class="">
      <img
        class="object-cover h-82 w-96 rounded"
        alt="hero"
        src="../assets/img/cover.jpg"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
}
</script>
