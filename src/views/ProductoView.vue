<template>
  <MenuComponent></MenuComponent>
  <NavComponent></NavComponent>
  <DetailProductoComponent></DetailProductoComponent>
</template>

<script>
import DetailProductoComponent from '@/components/DetailProductoComponent.vue';
import MenuComponent from '@/components/MenuComponent.vue';
import NavComponent from '@/components/NavComponent.vue';


export default {
name:'ProductoView',
components:{
MenuComponent,
NavComponent,
DetailProductoComponent


}
}
</script>

<style>

</style>