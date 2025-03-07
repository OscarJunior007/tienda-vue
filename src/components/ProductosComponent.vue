<template>
  <div>
      <!-- TRENDING -->
    <section class="container mx-auto py-16 px-4">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">TRENDING</h2>
            <p class="text-zinc-400 max-w-2xl mx-auto">
                Descubre nuestras cautivadoras fragancias - la mezcla perfecta de la naturaleza transformada en lujo moderno
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Product 1 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group">
                <div class="relative h-64 overflow-hidden">
                   <RouterLink to="/producto"> <img src="../assets/Perfumes/Eros Versace.jpg" alt="BLEU CHANEL" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"> </RouterLink> 
                </div>
                <div class="p-4">
                    <h3 class="font-medium">BLEU CHANEL</h3>
                    <p class="text-zinc-400 text-sm">Eau de Parfum</p>
                    <div class="flex justify-between items-center mt-4">
                        <span class="font-bold">$120.00</span>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded text-sm">
                            Añadir
                        </button>
                    </div>
                </div>
            </div>

            <!-- Product 2 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group">
                <div class="relative h-64 overflow-hidden">
                    <img src="product2.jpg" alt="AMBER ELEGANCE" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
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

            <!-- Product 3 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group">
                <div class="relative h-64 overflow-hidden">
                    <img src="product3.jpg" alt="MIDNIGHT OUD" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
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
          
           
        </div>

         <!-- Seccion 2 GORRAS -->
        <div class="text-center mb-12 mt-10">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Gorras</h2>
                <p class="text-zinc-400 max-w-2xl mx-auto">
                    Descubre nuestras exclusivas gorras - para todo tipo de ocasion
                </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Product 1 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group">
                <div class="relative h-64 overflow-hidden">
                    <img src="product1.jpg" alt="BLEU CHANEL" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                </div>
                <div class="p-4">
                    <h3 class="font-medium">BLEU CHANEL</h3>
                    <p class="text-zinc-400 text-sm">Eau de Parfum</p>
                    <div class="flex justify-between items-center mt-4">
                        <span class="font-bold">$120.00</span>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded text-sm">
                            Añadir
                        </button>
                    </div>
                </div>
            </div>

            <!-- Product 2 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group">
                <div class="relative h-64 overflow-hidden">
                    <img src="product2.jpg" alt="AMBER ELEGANCE" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
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

            <!-- Product 3 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group">
                <div class="relative h-64 overflow-hidden">
                    <img src="../assets/Gorras/Gorra1.webp" alt="MIDNIGHT OUD" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
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
            <!-- <div class="text-center mb-12"></div> -->
           

           
        </div>

        <div class="flex justify-center mt-12">
            <button class="border border-amber-700 text-amber-300 hover:bg-amber-900/20 font-bold py-2 px-4 rounded">
                Ver todos los productos
            </button>
        </div>
    </section>
  </div>
</template>

<script>
export default {
 name:'ProductosComponent'
}
</script>

<style>

</style>