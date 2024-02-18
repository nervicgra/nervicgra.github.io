<script setup>

import {RouterLink} from "vue-router";
</script>

<template>
  <v-app-bar height="140px">
    <img src="https://raw.githubusercontent.com/nervicgra/nervicgra.github.io/main/img/LogoTaxi.png" alt="" height="100px" class="pl-4">

    <RouterLink to="/">
      <v-btn class="font-weight-bold" height="50px" style="font-size: 30px" :ripple="false">
        Inicio
      </v-btn>
    </RouterLink>
    <RouterLink to="/about">
      <v-btn class="font-weight-bold pt-n16" height="50px" style="font-size: 30px" :ripple="false">
        Información
      </v-btn>
    </RouterLink>
  </v-app-bar>
</template>

<style scoped>

</style>