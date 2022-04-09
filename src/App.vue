<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
<!-- nav bar -->
<nav class="navbar navbar-expand-lg navbar-light bg-white">
  <div class="container">
    <a class="navbar-brand" href="#"><p class="fs-4 fw-bold"><span>E</span>-Hijrah</p></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a @click="this.$router.push('/')" class="nav-link" aria-current="page" href="#">Beranda</a>
        </li>
        <li class="nav-item">
          <a @click="this.$router.push({ name: 'about' })" class="nav-link" href="#">Panduan</a>
        </li>
        <li class="nav-item">
          <a @click="this.$router.push({ name: 'profile' })" class="nav-link" href="#">Profile</a>
        </li>
        <li class="nav-item">
          <a @click="this.$router.push({ name: 'developper' })" class="nav-link" href="#">Pengembang</a>
        </li>
        <li class="nav-item">
          <a @click="this.$router.push({ name: 'kontak' })" class="nav-link" href="#">Kontak</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
  <RouterView />
</template>

<style>
span{
  color: green;
}
.nav-item{
  margin: 10px;
}
</style>
