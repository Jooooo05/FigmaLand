<script>
  import { RouterLink, RouterView } from 'vue-router'
  import Navbar from '@/components/header/Navbar.vue'
  import Header from '@/components/header/HeaderMain.vue'
  import Features from '@/components/features/Feature.vue'
  import Organize from '@/components/organize/Organize.vue'
  import Prototyping from '@/components/prototyping/Prototyping.vue'
  import Partners from '@/components/partners/Partners.vue'

  export default {

    data() {
      return {
        
      };
    },

    components: {
        Navbar,
        Header,
        Features,
        Organize,
        Prototyping,
        Partners
      }
  };
</script>

<template>
  <main>
    <!-- header start -->
      <header class="bg-header-img w-full h-[800px] sm:h-[800px] md:h-[760px] lg:h-[640px] ">
        <Navbar />
        
        <Header /> 
      </header>
    <!-- header end -->

    <!-- Features start -->
      <div class="w-full ">
        <Features />
      </div>

      <div class="w-full">
        <Organize />
      </div>
    <!-- Features end -->

    <!-- Prototyping start -->
    <div class="w-full">
      <Prototyping />
    </div>
    <!-- Prototyping end -->

    <!-- Partners start -->
    <div class="w-full">
      <Partners />
    </div>
    <!-- Partners end -->
  </main>
</template>

<style scoped>
  .bg-header-img {
    background-image: url('@/assets/img/header.png');
    background-position: center bottom;
    background-repeat: no-repeat
  }
</style>
