<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import AppMain from './components/AppMain.vue';
import AppIconSection from './components/AppIconSection.vue';


export default {
  components: {
    AppHeader,
    AppFooter,
    AppMain,
    AppIconSection
  }
}

</script>


<template>
  <AppHeader />
  <AppMain />
  <AppIconSection />
  <AppFooter />
</template>


<style scoped></style>
