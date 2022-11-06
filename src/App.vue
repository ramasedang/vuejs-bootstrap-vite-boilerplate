<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <nav class="navbar navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand">VueJS</a>
        <form class="d-flex">
          <div class="p-2">
            <router-link to="/">Home</router-link>
          </div>
          <div class="p-2">
            <router-link to="/about">About</router-link>
          </div>
          <div class="p-2">
            <router-link to="/activity">Activity</router-link>
          </div>
        </form>
      </div>
    </nav>
  </div>
  <RouterView />
</template>

<style scoped>


</style>
