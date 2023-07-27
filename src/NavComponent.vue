<template>
     <Navbar>
    <template #logo>
      <Navbar>
        Al-karim
      </Navbar>
    </template>
    <template #default="{ isShowMenu }">
      <NavbarCollapse :isShowMenu="isShowMenu">
        <NavbarLink is-active>Home</NavbarLink>
        <NavbarLink>Services</NavbarLink>
        <NavbarLink>Pricing</NavbarLink>
        <NavbarLink>Contact</NavbarLink>
      </NavbarCollapse>
    </template>
    <template #right-side>
  
    </template>
  </Navbar>
</template>
<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>