<template>
  <h1 class="title">hello app</h1>
  <ul>
    <li>
      <router-link to="/home">Home</router-link>
    </li>
    <li>
      <router-link to="/about">About</router-link>
    </li>
  </ul>

  <router-view />
</template>

<script setup></script>

<style>
.title {
  color: red;
}
</style>
