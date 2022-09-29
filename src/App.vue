<script setup>
import Header from "./components/Header.vue"
import Footer from "./components/Footer.vue";
</script>
<template>
  <Header />
  <router-view />
  <Footer />
</template>

<style scoped>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
} */

#header a {
  font-weight: bold;
  color: #2c3e50;
}

#header a.router-link-exact-active {
  color: #42b983;
  background: red;
}
</style>
