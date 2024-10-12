<template>
  <div id="app">
    <Tarjeta />
  </div>
</template>

<script>
import Tarjeta from './components/Tarjeta.vue';

export default {
  components: {
    Tarjeta
  }
};
</script>

<style>
* {
  margin: 0;
}
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 60vh;
  font-size: 10px;
  font-family: sans-serif;
}
#app {
  display: flex;
  gap: 40px;
}
</style>
