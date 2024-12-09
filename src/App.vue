<template>
  <navbar/>
  <div class="auth-wrapper">
    <div class="auth-inner">
      <router-view/>
    </div>
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
</script>
