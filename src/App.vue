<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <v-app id="app">
    <v-main>
      <v-container fluid class="pa-0">
        <RouterView />
      </v-container>
    </v-main>
  </v-app>
</template>

<style scoped></style>
