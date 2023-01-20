<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  }
}

</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />


</template>

<style lang="scss">
@use '../src/assets/styles/general.scss' as *;
@import url('https://fonts.googleapis.com/css2?family=Lato&family=Montserrat&family=Open+Sans:wght@400;600&family=Roboto&display=swap');
</style>
