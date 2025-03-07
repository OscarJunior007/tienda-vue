<template>
  <div>
    <section class="relative h-[500px] bg-zinc-900 flex items-center justify-center overflow-hidden" style="width: 100%; height: 600px; background-size: cover; background-repeat: no-repeat; animation: encabezado 5s ease-in-out infinite;">
        <div class="relative z-10 text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-4">The Perfect Blend</h1>
            <p class="text-xl md:text-2xl text-amber-300">of Elegance & Sophistication</p>
        </div>
    </section>
  </div>
</template>

<script>
export default {
    name:'HeroSeccionComponent'
}
</script>

<style>

@keyframes encabezado {
  0% {
    background-image: url(../assets/Gorras/lll.webp);
  }

  50% {
    background-image: url(../assets/Gorras/imagenfondo.webp);
  }

  100% {
    background-image: url(../assets/Gorras/imagenperfume.webp);
  }
}
</style>