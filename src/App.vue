<template>
  <div id="app">
    <!--  <Home v-if="false" />
    <Pixabay /> -->
    <router-link to="/">Home</router-link> |
    <router-link to="/pixa">Imágenes</router-link>

    <!-- Aqui se va a pintar las rutas -->
    <router-view />
  </div>
</template>

<script>
/* import Home from "./components/Home";
import Pixabay from "./components/pixabay/PixaBay"; */
export default {
  name: "App",
  components: {
    /* Home,
    Pixabay, */
  },
};
</script>

<style >
</style>