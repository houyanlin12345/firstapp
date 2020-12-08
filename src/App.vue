<template>
  <div id="app">
    <img src="./assets/homepage.png" />
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app img {
  width: 100%;
}
</style>
