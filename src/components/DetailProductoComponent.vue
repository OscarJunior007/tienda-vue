<template>
  <div>
    <!-- Product Detail -->
    <section class="container mx-auto px-4 py-8" v-for="producto in producto_selecionado" :key="producto.id" >
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 lg:gap-12">
            <!-- Product Images -->
            <div class="space-y-4">
                <div class="bg-zinc-900 rounded-lg overflow-hidden">
                    <img :src="producto.imagen1" :alt="producto.nombre" class="w-full h-auto">
                </div>
                <div class="grid grid-cols-4 gap-2">
                    <div class="bg-zinc-900 rounded-lg overflow-hidden">
                        <img src="product-thumbnail-1.jpg" alt="BLEU CHANEL thumbnail 1" class="w-full h-auto">
                    </div>
                    <div class="bg-zinc-900 rounded-lg overflow-hidden">
                        <img src="product-thumbnail-2.jpg" alt="BLEU CHANEL thumbnail 2" class="w-full h-auto">
                    </div>
                    <div class="bg-zinc-900 rounded-lg overflow-hidden">
                        <img src="product-thumbnail-3.jpg" alt="BLEU CHANEL thumbnail 3" class="w-full h-auto">
                    </div>
                    <div class="bg-zinc-900 rounded-lg overflow-hidden">
                        <img src="product-thumbnail-4.jpg" alt="BLEU CHANEL thumbnail 4" class="w-full h-auto">
                    </div>
                </div>
            </div>

            <!-- Product Info -->
            <div class="space-y-6" >
                <div>
                    <h1 class="text-3xl font-bold">{{ producto.nombre }}</h1>
                    <p class="text-zinc-400">{{ producto.minidescripcion }}</p>
                </div>

                <div class="flex items-center gap-2">
                    <div class="flex">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-amber-400" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-amber-400" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-amber-400" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-amber-400" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-zinc-600" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                        </svg>
                    </div>
                    <span class="text-sm text-zinc-400">(42 reseñas)</span>
                </div>

                <div class="text-2xl font-bold">${{producto.precio}}</div>

                <div class="space-y-4">
                    <div>
                        <h3 class="font-medium mb-2">Tamaño</h3>
                        <div class="flex gap-3">
                            <label class="flex items-center">
                                <input type="radio" name="size" value="50ml" class="sr-only" checked>
                                <span class="px-3 py-2 rounded-full border border-zinc-700 cursor-pointer hover:border-amber-300">50ml</span>
                            </label>
                            <label class="flex items-center">
                                <input type="radio" name="size" value="100ml" class="sr-only">
                                <span class="px-3 py-2 rounded-full border border-zinc-700 cursor-pointer hover:border-amber-300">100ml</span>
                            </label>
                            <label class="flex items-center">
                                <input type="radio" name="size" value="150ml" class="sr-only">
                                <span class="px-3 py-2 rounded-full border border-zinc-700 cursor-pointer hover:border-amber-300">150ml</span>
                            </label>
                        </div>
                    </div>

                    <div>
                        <h3 class="font-medium mb-2">Cantidad</h3>
                        <div class="flex items-center">
                            <button class="bg-zinc-900 text-white px-3 py-2 rounded-l-md">-</button>
                            <input type="number" value="1" min="1" class="bg-zinc-800 text-white text-center w-16 py-2 border-y border-zinc-700">
                            <button class="bg-zinc-900 text-white px-3 py-2 rounded-r-md">+</button>
                        </div>
                    </div>
                </div>

                <div class="flex flex-col sm:flex-row gap-4">
                    <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded flex-1">
                        Añadir al carrito
                    </button>
                    <button class="border border-zinc-700 hover:bg-zinc-800 text-white font-bold py-2 px-4 rounded flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M3.172 5.172a4 4 0 015.656 0L10 6.343l1.172-1.171a4 4 0 115.656 5.656L10 17.657l-6.828-6.829a4 4 0 010-5.656z" clip-rule="evenodd" />
                        </svg>
                        Añadir a favoritos
                    </button>
                </div>

                <div class="border-t border-zinc-800 pt-6">
                    <div class="flex border-b border-zinc-800">
                        <button class="py-2 px-4 font-medium border-b-2 border-amber-300">Descripción</button>
                        <button class="py-2 px-4 font-medium text-zinc-400">Detalles</button>
                        <button class="py-2 px-4 font-medium text-zinc-400">Reseñas</button>
                    </div>
                    <div class="py-4">
                        <p class="text-zinc-300">
                            {{ producto.descripcion }}
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
  </div>
</template>

<script>
export default {
name:'DetailProductoComponent',

data(){
    return{
            producto_selecionado:[],
            
    }
},
created: function() {
       let producto = localStorage.getItem("producto")
       let objeto = JSON.parse(producto)
       this.producto_selecionado.push(objeto)
       console.log("este es el producto",this.producto_selecionado)
}
}
</script>

<style>

</style>