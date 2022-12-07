<script setup>
import Navbar from './components/Navbar.vue';
</script>

<template>
  <main class="main">
    <div class="sidebar">
      <Navbar />
    </div>
    <div class="content">
      <div class="content-header">
        <h1 class="title">title</h1>
      </div>
      <div class="container">
        <router-view></router-view>
      </div>
    </div>
  </main>
</template>

<style scoped>
.main {
  display: flex;
}
.content-header {
  width: 100%;
  position: absolute;
  background-color: white;
  height: 6em;
}
.container {
  background-color: grey;
  margin-top: 6em;
}
</style>
