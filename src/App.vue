<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
* {
  box-sizing: border-box;
}
html, body, #app {
  width: 100%;
  height: 100%;
  margin: 0;
}
#app {
  font-family: Helvetica, Arial, sans-serif;
  text-align: center;
}
</style>
