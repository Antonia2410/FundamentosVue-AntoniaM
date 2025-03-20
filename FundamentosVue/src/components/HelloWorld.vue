<script setup>
//importarcion del 1card 
import card from './Card.vue';
//importacion de car principal 
import cardPrincipal from './CardPrincipal.vue';

</script>

<template>
  
  <div class="container">

    <h1 class="text-center">FLORES</h1>
   
  <!-- cierre de row -->
  <card-principal/>
  <!-- segundo row -->
 <card/>
 <card/>
  </div>
  
</template>

<style scoped>

</style>