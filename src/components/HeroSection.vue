<script setup>
// import {defineProps} from 'vue';
// const props = defineProps({
// });
</script>

<template>
  <section>
    <nav 
      class="bg-gray-50 flex flex-col text-center sm:flex-row sm:text-left sm:justify-center py-4 sm:items-baseline w-full p-8"
    >
    <div>
        <router-link
          to="/"
          class="text-sm no-underline border-b border-white hover:border-yellow-400 hover:text-yellow-400 ml-4 md:ml-6 inline-block"
          >All</router-link
        >
        <router-link
          to="/branding-goal"
          class="text-sm no-underline border-b border-white hover:border-yellow-400 hover:text-yellow-400 ml-4 md:ml-6 inline-block"
          > Brandina Goal
        </router-link>
        <a
          to="/#"
          class="text-sm no-underline border-b border-white hover:border-yellow-400 hover:text-yellow-400 ml-4 md:ml-6 inline-block"
          >Photograony
        </a>
        <a
          to="/#"
          class="text-sm no-underline border-b border-white hover:border-yellow-400 hover:text-yellow-400 ml-4 md:ml-6 inline-block"
          >True Pertectior
        </a>
        <a
          to="/#"
          class="text-sm no-underline border-b border-white hover:border-yellow-400 hover:text-yellow-400 ml-4 md:ml-6 inline-block"
          >Web Desigr
        </a>
    </div>
    </nav>
  </section>
</template>
<style scoped>
a.router-link-exact-active {
  color: #fad215;
}

</style>
