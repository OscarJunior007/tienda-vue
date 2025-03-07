<template>
  <div class="min-h-screen bg-black text-white">
    <HomeComponent></HomeComponent>
    <MenuComponent></MenuComponent>
    <NavComponent></NavComponent>
    <HereSeccionComponent></HereSeccionComponent>
    <ProductosComponent></ProductosComponent>
    <ArticuloDestacadoComponent></ArticuloDestacadoComponent>
    <InformacionComponent></InformacionComponent>
    <FooterComponent></FooterComponent>
  </div>
</template>

<script>
import ArticuloDestacadoComponent from '@/components/ArticuloDestacadoComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
import HereSeccionComponent from '@/components/HereSeccionComponent.vue';
import HomeComponent from '@/components/HomeComponent.vue'
import InformacionComponent from '@/components/InformacionComponent.vue';
import MenuComponent from '@/components/MenuComponent.vue'
import NavComponent from '@/components/NavComponent.vue';
import ProductosComponent from '@/components/ProductosComponent.vue';
export default {

 name:'HomeTiendaView',

 components:{
    HomeComponent,
    MenuComponent,
    NavComponent,
    HereSeccionComponent,
    ProductosComponent,
    ArticuloDestacadoComponent,
    InformacionComponent,
    FooterComponent
 }
}
</script>

<style scoped>

</style>