<script setup>
import { RouterView } from 'vue-router'
import AppBar from "@/components/AppBar.vue";
import CustomFooter from "@/components/CustomFooter.vue";
</script>

<template>
  <v-app class="text-black">
    <AppBar/>
    <RouterView />
    <CustomFooter/>
  </v-app>
</template>

<style scoped>
</style>
