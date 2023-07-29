<script setup>
import NavComponent from './NavComponent.vue'
import HelloComponent from './HelloComponent.vue'
import HeaderComponent from './HeaderComponent.vue'
import HellooComponent from './HellooComponent.vue'
import ContackComponent from './ContackComponent.vue'
import FooterComponent from './FooterComponent.vue'
</script>
<template>
  <div class="navbar" style="background: white;">
    <NavComponent></NavComponent>
  </div>
  <div class="isi" style="background: white;">
    <HeaderComponent></HeaderComponent>
  </div>
  <br>
  <div class="back" style="background: white;">
    <HelloComponent></HelloComponent>
  </div>
  <br>
  <div class="back1" style="background: white;">
    <HellooComponent></HellooComponent>
  </div>
  <div class="back1" style="background: white;">
    <ContackComponent></ContackComponent>
  </div>
  <br>
  <div class="down" >
    <FooterComponent></FooterComponent>
  </div>
</template>
