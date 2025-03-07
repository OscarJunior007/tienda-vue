<template>
  <div>
      <!-- TRENDING -->
    <section class="container mx-auto py-16 px-4">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">PERFUMES</h2>
            <p class="text-zinc-400 max-w-2xl mx-auto">
                Descubre nuestras cautivadoras fragancias - la mezcla perfecta de la naturaleza transformada en lujo moderno
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8"  > 
            <!-- Product 1 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group" v-for="producto in perfumes" :key="producto.id">
                <div class="relative h-64 overflow-hidden">
                     <img :src="producto.imagen1" :alt="producto.nombre" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"> 
                </div>

                <div class="p-4">
                    <h3 class="font-medium">{{producto.nombre}}</h3>
                    <p class="text-zinc-400 text-sm">{{producto.minidescripcion}}</p>
                    <div class="flex justify-between items-center mt-4">
                        <span class="font-bold">$ {{producto.precio}}</span>
                        <RouterLink to="/producto">  <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded text-sm" @click="getProducts(producto)">
                            Añadir
                        </button> </RouterLink>
                    </div>
                </div>
            </div>
        </div>

         <!-- Seccion 2 GORRAS -->
        <div class="text-center mb-12 mt-10">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Gorras</h2>
                <p class="text-zinc-400 max-w-2xl mx-auto">
                    Gorras Exclusivas - Estilo y Autenticidad 🧢🔥
                </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Product 1 -->
            <div class="bg-zinc-900 border border-zinc-800 rounded-lg overflow-hidden group" v-for="producto in gorras" :key="producto.id">
                <div class="relative h-64 overflow-hidden">
                    <img :src="producto.imagen1" :alt="producto.nombre"  class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                </div>
                <div class="p-4">
                    <h3 class="font-medium">{{producto.nombre}}</h3>
                    <p class="text-zinc-400 text-sm">{{producto.minidescripcion}}</p>
                    <div class="flex justify-between items-center mt-4">
                        <span class="font-bold">${{ producto.precio }}</span>
                        <button class="bg-amber-700 hover:bg-amber-600 text-white font-bold py-2 px-4 rounded text-sm">
                            Añadir
                        </button>
                    </div>
                </div>
            </div>
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
 name:'ProductosComponent',

 data(){
    return{
    perfumes:  [
    {
    id: 1,
    nombre: "Ero Versace Blue",
    imagen1 : "https://media.superdrug.com//medias/sys_master/prd-images/h59/h0c/11429582372894/prd-ls1-711957_600x600/prd-ls1-711957-600x600.jpg",
    imagen2 : "",
    imagen3 : "",
    imagen4 : "",
    precio : "800000",
    minidescripcion : "Fresca, vibrante y seductora, con menta, manzana y vainilla.",
    descripcion :  "HOMENAJE A UNA LEYENDA. El Nike Air Force 1 Mid LE trae de vuelta al ícono de la cancha del 82 en un estilo completamente blanco o negro para usarlo todos los días. La durabilidad, la sensación y la amortiguación Air-Sole siguen ahí con este estilo clásico que conoces y te encanta.",
},
{
    id: 2,
    nombre: "Ero Versace Flame",
    imagen1 : "https://disfragancias.com/cdn/shop/files/flame_2.png?v=1725725242",
    imagen2 : "",
    imagen3 : "",
    imagen4 : "",
    precio : "830000",
    minidescripcion : "Intenso y apasionado, con mandarina, pimienta y vainilla.",
    descripcion :  "¿Puedes ver el futuro? Avanza rápido con el diseño vanguardista del Nike Interact Run. Está diseñado con todas las bondades del running que necesitas: una parte superior ligera de Flyknit, una entresuela de espuma suave y comodidad donde importa. ",
},
{
    id: 3,
    nombre: "Toy boy - Moschino",
    imagen1 : "https://disfragancias.com/cdn/shop/files/moschino_2.png?v=1725739176",
    imagen2 : "",
    imagen3 : "",
    imagen4 : "",
    precio : "850000",
    minidescripcion : "Especiado, amaderado y seductor, con bergamota y vetiver.",
    descripcion :  "Mantén tu equipo bajo control con una mochila inspirada en el Air Max 95 icónico. Con una organización práctica que incluye una funda para laptop y un estuche para botellas de agua, esta mochila te acompaña. Las correas acolchadas regulables mantienen la comodidad, ya sea que vayas a un partido de béisbol o salgas con amigos.",
}
],

gorras:  [
    {
    id: 1,
    nombre: "Gorra Amiri",
    imagen1 : "https://wol-store.com/wp-content/uploads/2023/09/IMG_2024-07-27-194554.jpg",
    imagen2 : "",
    imagen3 : "",
    imagen4 : "",
    precio : "65000",
    minidescripcion : "Gorra Amiri, diseño premium con estilo urbano y logo icónico. 🧢✨",
},
{
    id: 2,
    nombre: "WxB Edition Two",
    imagen1 : "https://wmerchshop.com/cdn/shop/files/portada_gorra_amarilla_14e86c7e-4be2-4952-9e09-cd22fd0f8032_900x.jpg?v=1724543026",
    imagen2 : "",
    imagen3 : "",
    imagen4 : "",
    precio : "270000",
    minidescripcion : "WxB Edition  + Pin Blessd+ Sticker WSonud + Sticker WB",
},
{
    id: 3,
    nombre: "Gorra westcol x Blessd",
    imagen1 : "https://imgs.search.brave.com/kvATZExW67kBzpkIefVyLVwS_kJeL4kegaBCehAF0f0/rs:fit:860:0:0:0/g:ce/aHR0cDovL2NvbGNv/bXByYS5jb20vd3At/Y29udGVudC91cGxv/YWRzLzIwMjQvMTIv/MTMzODYyOS5wbmc",
    imagen2 : "",
    imagen3 : "",
    imagen4 : "",
    precio : "210000",
    minidescripcion : "Gorra edición limitada Westcol x Blessd, diseño urbano y logo bordado. 🧢🔥",
}
],
}
},
methods: {
    getProducts(producto) {
        console.log(producto)
        let objetoJson = JSON.stringify(producto)
        console.log("Esto es el objeto",objetoJson)
        localStorage.setItem("producto",objetoJson)
    }
}
}

</script>

<style>

</style>