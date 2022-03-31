<template>
  <Home/>
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Home,
  }
}
</script>

<style>
@font-face {
  font-family: "Calibre";
  src: local("Calibre"),
   url(./fonts/NBS-FONTS/WOFF2/Calibre/calibre-regular.woff2) format("woff2");
}

@font-face {
  font-family: "Calibre Bold";
  src: local("Calibre"),
   url(./fonts/NBS-FONTS/WOFF2/Calibre/calibre-bold.woff2) format("woff2");
}
@font-face {
  font-family: "Epicene Display Black";
  src: local("Epicene Display"),
   url(./fonts/NBS-FONTS/WOFF2/Epicene\ Display/epicene-display-black.woff2) format("woff2");
}
@font-face {
  font-family: "Epicene Text Bold";
  src: local("Epicene Text"),
   url(./fonts/NBS-FONTS/WOFF2/Epicene\ Text/epicene-text-bold.woff2) format("woff2");
}
@font-face {
  font-family: "Epicene Text";
  src: local("Epicene Text"),
   url(./fonts/NBS-FONTS/WOFF2/Epicene\ Text/epicene-text-regular.woff2) format("woff2");
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.full-height {
  min-height: 90vh;
}

html, body {
    max-width: 100%;
    overflow-x: hidden;
    padding: 0px, 150px, 0px, 140px !important;
}
</style>
