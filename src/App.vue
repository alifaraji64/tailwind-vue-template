<template>
  <div id="app">
    <div id="nav">
      <h1 class="text-red-200">hello from tailwind</h1>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>

@import './assets/css/compiled.css';
</style>
