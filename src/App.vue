<!-- App.vue -->
<template>
  <div id="app">
    <router-link class="link" :to="{ path: '/' }">Profile </router-link> |
    <router-link class="link" :to="{ path: '/contact' }">Contact </router-link>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  margin: 0px;
  text-align: center;
}
.link {
  background-color: #d8d1d1;
  color: rgb(0, 0, 0);
  padding: 14px;
  text-align: center;
  margin-right: 5px;
  text-decoration: none;
  display: inline-block;
  border-radius: 50%;
  font-family: "Comfortaa";
}

body {
  background-color: #25282b;
}
</style>
