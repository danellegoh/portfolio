<script setup>
import { RouterLink, RouterView } from 'vue-router'
import profile from './components/profile.vue'
import navbar from './components/navbar.vue'
</script>

<template>
  <div>
    <navbar />
  </div>

  <RouterView />
</template>

<script>
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap/dist/js/bootstrap.min.js";

</script>

<style>
  

</style>
