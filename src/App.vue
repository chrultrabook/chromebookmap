<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import vuerouter from '../node_modules/vue-router'

console.log("[App.vue]", `Hello world from Electron ${process.versions.electron}!`)
</script>

<template>
  <div>
    <a href="https://coolstar.org/" target="_blank">
      <span>Coolstar.org</span>
    </a>
  <router-view></router-view>
  </div>
</template>

<style></style>
