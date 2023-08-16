<script setup>
import HeroSection from '../components/HeroSection.vue';
import CompanyInfo from '../components/CompanyInfo.vue';
import NewsSection from '../components/NewsSection.vue';
import Aside from '../components/Aside.vue';
</script>

<template>
  <main>
    <HeroSection />
    <CompanyInfo />
    <div class="flex xl:flex-row flex-col-reverse">
      <NewsSection />
        <Aside />
    </div>
  </main>
</template>
