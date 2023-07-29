<!-- <script setup>
import HelloWorld from './components/HelloWorld.vue'
</script> -->

<!-- <template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template> -->
<!-- <template>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</template> -->


<template>
  <!-- <dropdown text="Click me" placement="top">
    <list-group>
      <list-group-item>Item #1</list-group-item>
      <list-group-item>Item #2</list-group-item>
      <list-group-item>Item #3</list-group-item>
    </list-group>
  </dropdown> -->

  <div>
    <NavbarComponent class="shadow-md">
      <template #title>
        <h3 class="font-semibold text-lg ms-2">
          Web Muhamaddika
        </h3>
      </template>
    </NavbarComponent>
    <HeaderComponent>
    </HeaderComponent>
    <BodyComponent>
    </BodyComponent>
    <KeterampilanComponent></KeterampilanComponent>
    <ContactComponent></ContactComponent>
    <FooterComponent>
    <template #text1>
      Copyright &COPY; 2023
      <a href="https://www.instagram.com/mhmmddkaaa_/" class="text-blue-700 hover:underline" target="_blank">mhmmddkaaa_</a>
    </template>
  </FooterComponent>
  </div>
</template>


<script setup>
import { Dropdown, ListGroup, ListGroupItem } from 'flowbite-vue'
import NavbarComponent from './components/NavbarComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import ContactComponent from './components/ContactComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import KeterampilanComponent from './components/KeterampilanComponent.vue';
import BodyComponent from './components/BodyComponent.vue'
</script>



<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
