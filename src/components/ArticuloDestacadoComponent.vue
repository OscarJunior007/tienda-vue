<template>
  <div>
    <section class="bg-zinc-900 py-16">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4"> TOP VENTAS </h2>
                <p class="text-zinc-400 max-w-2xl mx-auto">
                    Descubre nuestra colección de articulos mas destacados
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="relative h-[400px] rounded-lg overflow-hidden">
                    <img src="https://imgs.search.brave.com/kvATZExW67kBzpkIefVyLVwS_kJeL4kegaBCehAF0f0/rs:fit:860:0:0:0/g:ce/aHR0cDovL2NvbGNv/bXByYS5jb20vd3At/Y29udGVudC91cGxv/YWRzLzIwMjQvMTIv/MTMzODYyOS5wbmc" alt="Gorra westcol x Blessd" class="w-full h-full object-cover">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex flex-col justify-end p-6">
                        <h3 class="text-2xl font-bold mb-2">$210K</h3>
                        <p class="text-zinc-300 mb-4">Gorra edición limitada Westcol x Blessd, diseño</p>
                        <div class="flex justify-center gap-4">
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded w-fit">
                            Cantidades Vendidas <br> +50M
                        </button>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded w-fit">
                            Cantidades Disponible <br> 10M
                        </button>
                        </div>
                    </div>
                </div>

                <div class="relative h-[400px] rounded-lg overflow-hidden">
                    <img src="https://disfragancias.com/cdn/shop/files/moschino_2.png?v=1725739176" alt="Toy boy - Moschino" class="w-full h-full object-cover">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex flex-col justify-end p-6">
                        <h3 class="text-2xl font-bold mb-2">$850K</h3>
                        <p class="text-zinc-300 mb-4">Especiado, amaderado y seductor, con bergamota y vetiver.</p>
                        <div class="flex justify-center gap-4">
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded w-fit">
                            Cantidades Vendidas <br> +35M
                        </button>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded w-fit">
                            Cantidades Disponible <br> 2M
                        </button>
                        </div>
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