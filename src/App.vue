<template>
  <SideNavBar />

  <main class="main-content position-relative max-height-vh-100 h-100 border-radius-lg ">

    <div class="container-fluid py-2">
      <NavBar />

      <RouterView />
    </div>

  </main>

  <SettingsPlugin />
</template>

<script setup lang="ts">
import { RouterView } from 'vue-router'
import SideNavBar from "./components/SideNavBar.vue";
import SettingsPlugin from "./components/SettingsPlugin.vue";
import NavBar from "./components/NavBar.vue";
</script>
