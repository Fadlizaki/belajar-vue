<template>
     <Navbar>
    <template #logo>
      <Navbar>
        AL- KARIM
      </Navbar>
    </template>
    <template #default="{ isShowMenu }">
      <NavbarCollapse :isShowMenu="isShowMenu">
        <NavbarLink is-active>Beranda</NavbarLink>
        <NavbarLink>kontak</NavbarLink>
        <NavbarLink>Tentang</NavbarLink>
      </NavbarCollapse>
    </template>
  </Navbar>
</template>
<script setup>
import { Navbar, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>