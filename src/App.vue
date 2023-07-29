<script setup>
import AppHeader from './components/appHeader.vue';
import AppFooter from './components/appFooter.vue';
import AppWho from './components/appWho.vue';
import AppModule from './components/appModule.vue';
import AppCarrosel from './components/appCarrosel.vue';
import AppBackToTop from './components/appBackToTop.vue';
import AppResults from './components/appResults.vue';
import AppInsights from './components/appInsights.vue';

</script>

<template>
  <AppHeader />
  <AppBackToTop />
  <AppWho />
  <AppModule />
  <AppCarrosel/>
  <AppResults />
  <AppInsights />
  <AppFooter />
</template>

<style scoped>


body{
  background-color: #f4f4f4;
}



*{
    margin: 0;
    padding: 0;
}
</style>
