<template>
  <div class="min-h-screen bg-black text-white">
  <MenuComponent></MenuComponent>
  <NavComponent></NavComponent>
  <DetailProductoComponent></DetailProductoComponent>
  <OtrasOpcionesComponent></OtrasOpcionesComponent>
  <FooterComponent></FooterComponent>
</div>
</template>

<script>
import DetailProductoComponent from '@/components/DetailProductoComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
import MenuComponent from '@/components/MenuComponent.vue';
import NavComponent from '@/components/NavComponent.vue';
import OtrasOpcionesComponent from '@/components/OtrasOpcionesComponent.vue';


export default {
name:'ProductoView',
components:{
MenuComponent,
NavComponent,
DetailProductoComponent,
FooterComponent,
OtrasOpcionesComponent


}


}
</script>

<style>

</style>