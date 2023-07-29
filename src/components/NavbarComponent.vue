<template>
    <Navbar>
      <template #logo>
        <img class="w-10 h-10 rounded-full hover:scale-125" src="/img/ftoaku.jpg" alt="Rounded avatar">
        <h3 class="ms-4 font-semibold text-lg">Muhamaddika</h3>
      </template>

      <template #default="{ isShowMenu }">
        <NavbarCollapse :isShowMenu="isShowMenu" class="ms-auto">
                <NavbarLink link="#home">Home</NavbarLink>
                <NavbarLink link="#bio">Biodata</NavbarLink>
                <NavbarLink link="#skill">Keterampilan</NavbarLink>
                <NavbarLink link="#kontak">Kontak</NavbarLink>
            </NavbarCollapse>
      </template>
    </Navbar>
  </template>
  
  <script setup>
  import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue';
  </script>
  