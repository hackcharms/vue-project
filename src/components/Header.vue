<script setup>
// import { defineProps } from "vue";
// const props = defineProps({});
</script>

<template>
  <nav
    class="bg-gray-50 font-sans flex flex-col text-center sm:flex-row sm:text-left sm:justify-between py-4 px-6 sm:items-baseline w-full"
  >
    <div class="mb-2 sm:mb-0">
      <router-link
        to="/"
        class="inline-flex md:block text-center md:text-left justify-center text-2xl no-underline text-grey-darkest hover:text-blue-dark"
      >
        <img
          :src="require('../assets/images/brand_logo.png')"
          alt="brand Logo"
        />
      </router-link>
    </div>
    <div id="header">
      <router-link
        to="/"
        class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-6"
        >Home</router-link
      >
      <router-link
        to="/about"
        class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-6"
        >About
      </router-link>
      <a
        to="#"
        class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-6"
        >Services
      </a>
      <a
        to="#"
        class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-6"
        >Portfolio
      </a>
      <a
        to="#"
        class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-6"
        >Contact
      </a>
      <a
        to="#"
        class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-6"
        >Blog
      </a>
    </div>
  </nav>
</template>
<style scoped>
a {
  border-bottom: 2px;
  border-color: transparent;
}
#header a.router-link-exact-active {
  border-bottom: 2px solid;
  border-color: #fad215;
} 

#header a.router-link-active {
  border-bottom: 2px solid;
  border-color: #fad215;
} 
</style>
