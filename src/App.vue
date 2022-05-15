<template>
  <div id="app">
    <router-link id="bg-link" class="link" :to="{ path: '/' }"
      >Profile</router-link
    >
    <router-link id="bg-link" class="link" :to="{ path: '/contact' }"
      >Contact</router-link
    >
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#bg-link {
  background-color: azure;
  margin-right: 5px;
  color: darkslategray;
}
#app {
  margin: 0px;
  text-align: start;
}
.link {
  display: inline-block;
  padding: 10px;
  text-decoration: none;
  color: inherit;
}

body {
  background-color: pink;
}
</style>