<script setup>
import { ref } from "vue";
import NavbarVue from "./components/Navbar.vue";

import { RouterView } from "vue-router";

  const aData = ref("Remember that this is from App.vue");
</script>

<template>
  <NavbarVue/>
  <RouterView/>
  <h1 class="text-2xl text-center">{{aData}}</h1>
</template>