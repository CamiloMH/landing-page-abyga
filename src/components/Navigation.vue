<template>
   <nav class="container flex items-center py-4 mt-4 sm:mt-12">
    
    <a href="#logo"><div class="py-1"><img src="../assets/images/logo.png" width="300" alt="podcast logo" id="logo"></div></a>
    <ul class="hidden sm:flex flex-1 justify-end items-center gap-12 text-bookmark-blue uppercase text-xs">
      
        
        <li class="cursor-pointer text-white"><a href="#features">Características</a></li>
        <li class="cursor-pointer text-white"><a href="#contact">Contacto</a></li>
        <button type="button" class="abyga-background text-white rounded-md px-7 py-3 uppercase">Login</button>
      </ul>
      <div class="flex sm:hidden flex-1 justify-end"><i class="text-xl fas fa-bars text-white cursor-pointer"></i></div>
  </nav>
</template>

<script setup>


</script>

<style scoped>
  .abyga-background {
    background-color: #3e823b;
  }
</style>


