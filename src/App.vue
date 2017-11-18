<template>
  <div id="app">
    <img src="http://www.gravatar.com/avatar/6c1aa726eee0183a8820a97a515eb3ab?s=200">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

img {
  -webkit-transition: -webkit-transform .8s ease-in-out;
          transition:         transform .8s ease-in-out;
}
img:hover {
  -webkit-transform: rotate(360deg);
          transform: rotate(360deg);
}
</style>
