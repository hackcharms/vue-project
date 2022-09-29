<template>
  <div class="home">
    <div class="my-10">
      <div class="flex flex-col items-center mb-10">
        <h1 class="text-xl md:text-xxl font-bold">Latest Work</h1>
        <span
          class="h-1 w-12 md:w-24 border-b-2 md:border-b-4 border-yellow-400 md:mt-4"
        ></span>
      </div>
      <article class="text-center px-20 md:px-80 text-sm md:text-base">
        &lt;p&gt; Excepteur sint occaecat cupidatat non oroident, sunt in culba
        aul officia deserunt mollit anim id est laborum. Sed ut perspiciatis
        unde omnis iste natus &lt;/p&gt;
      </article>
    </div>

    <HeroSection />
    <div class="px-10 md:px-20 lg:px-32">
      <router-view></router-view>
    </div>
    <div class="my-10 bg-gray-50">
      <div class="flex flex-col items-center mb-10">
        <h1 class="text-xl md:text-xxl font-bold">Work Experiences</h1>
        <span
          class="h-1 w-12 md:w-24 border-b-2 md:border-b-4 border-yellow-400 md:mt-4"
        ></span>
      </div>
      <article class="text-center px-20 md:px-80">
        Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
        officia deserunt mollit anim id est laborum. Sed ut perspiciatis unde
        omnis iste natus
      </article>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HeroSection from "../components/HeroSection.vue";
// import Article from "../components/Article.vue";

export default {
  name: "Home",
  components: {
    HeroSection,
    // Article,
  },
};
</script>
