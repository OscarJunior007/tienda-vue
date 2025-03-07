<template>
  <div>
    <section class="bg-zinc-900 py-16">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">COLECCIÓN EXCLUSIVA</h2>
                <p class="text-zinc-400 max-w-2xl mx-auto">
                    Descubre nuestra colección de fragancias premium, elaboradas con los ingredientes más finos
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="relative h-[400px] rounded-lg overflow-hidden">
                    <img src="collection-men.jpg" alt="Colección para hombre" class="w-full h-full object-cover">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex flex-col justify-end p-6">
                        <h3 class="text-2xl font-bold mb-2">PARA ÉL</h3>
                        <p class="text-zinc-300 mb-4">Fragancias sofisticadas para el hombre moderno</p>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded w-fit">
                            Explorar
                        </button>
                    </div>
                </div>

                <div class="relative h-[400px] rounded-lg overflow-hidden">
                    <img src="collection-women.jpg" alt="Colección para mujer" class="w-full h-full object-cover">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex flex-col justify-end p-6">
                        <h3 class="text-2xl font-bold mb-2">PARA ELLA</h3>
                        <p class="text-zinc-300 mb-4">Fragancias elegantes que capturan la esencia femenina</p>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded w-fit">
                            Explorar
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
  </div>
</template>

<script>
export default {
 name:'ArticuloDestacadoComponent'
}
</script>

<style>

</style>