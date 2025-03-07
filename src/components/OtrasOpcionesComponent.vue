<template>
  <div>
    <section class="container mx-auto py-12 px-4">
        <h2 class="text-2xl font-bold mb-6">También te puede interesar</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-6">
            <!-- Product 1 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group">
                <div class="relative h-64 overflow-hidden">
                    <img src="related-product-1.jpg" alt="AMBER ELEGANCE" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                </div>
                <div class="p-4">
                    <h3 class="font-medium">AMBER ELEGANCE</h3>
                    <p class="text-zinc-400 text-sm">Eau de Parfum</p>
                    <div class="flex justify-between items-center mt-4">
                        <span class="font-bold">$95.00</span>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded text-sm">
                            Añadir
                        </button>
                    </div>
                </div>
            </div>

            <!-- Product 2 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group">
                <div class="relative h-64 overflow-hidden">
                    <img src="related-product-2.jpg" alt="MIDNIGHT OUD" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                </div>
                <div class="p-4">
                    <h3 class="font-medium">MIDNIGHT OUD</h3>
                    <p class="text-zinc-400 text-sm">Eau de Parfum</p>
                    <div class="flex justify-between items-center mt-4">
                        <span class="font-bold">$150.00</span>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded text-sm">
                            Añadir
                        </button>
                    </div>
                </div>
            </div>

            <!-- Product 3 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group">
                <div class="relative h-64 overflow-hidden">
                    <img src="related-product-3.jpg" alt="ROSE ELIXIR" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                </div>
                <div class="p-4">
                    <h3 class="font-medium">ROSE ELIXIR</h3>
                    <p class="text-zinc-400 text-sm">Eau de Parfum</p>
                    <div class="flex justify-between items-center mt-4">
                        <span class="font-bold">$110.00</span>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded text-sm">
                            Añadir
                        </button>
                    </div>
                </div>
            </div>

            <!-- Product 4 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group">
                <div class="relative h-64 overflow-hidden">
                    <img src="related-product-4.jpg" alt="AQUA VITAE" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                </div>
                <div class="p-4">
                    <h3 class="font-medium">AQUA VITAE</h3>
                    <p class="text-zinc-400 text-sm">Eau de Parfum</p>
                    <div class="flex justify-between items-center mt-4">
                        <span class="font-bold">$85.00</span>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded text-sm">
                            Añadir
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
    name: 'OtrasOpcionesComponent'
}
</script>

<style>

</style>