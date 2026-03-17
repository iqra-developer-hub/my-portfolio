<template>
  <HeaderComponent/>
<main>
    <RouterView />
  </main>
  
  <FooterComponent/>
</template>


<script setup>
import HeaderComponent from './components/Header-component.vue';
import FooterComponent from './components/Footer-component.vue';
</script>

<style>
html, body{
  height:100%;
  margin:0;
}

body{
  display:flex;
  flex-direction:column;
}

main{
  flex:1;
}
</style>