<script setup>
// import {defineProps} from 'vue';
// const props = defineProps({
// });
</script>

<template>
  <section class="grid grid-cols-2 gap-4">
    <div class="grid grid-cols-1 gap-4">
      <img :src="require('../assets/images/2.jpg')" alt="images" class="w-full h-full" />
      <img :src="require('../assets/images/9.jpg')" alt="images" class="w-full h-full" />
    </div>
    <div class="grid grid-cols-2 gap-4">
      <img :src="require('../assets/images/1.jpg')" alt="images" class="w-full h-full" />
      <img :src="require('../assets/images/5.jpg')" alt="images" class="w-full h-full" />
      <img :src="require('../assets/images/4.jpg')" alt="images" class="w-full h-full" />
      <img :src="require('../assets/images/6.jpg')" alt="images" class="w-full h-full" />
      <img :src="require('../assets/images/3.jpg')" alt="images" class="w-full h-full" />
      <img :src="require('../assets/images/7.jpg')" alt="images" class="w-full h-full" />
    </div>
  </section>
</template>
<style scoped></style>
