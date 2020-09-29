<template>
  <div id="app">
    <div id="nav" class="text-center">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
    </div>
    <router-view/>
  </div>
</template>
<style>
body {
  background-color: rgba(227, 107, 238, 0.74);
}
</style>
