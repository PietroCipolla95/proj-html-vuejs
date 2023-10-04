<script>

import AppHeader from './components/AppHeader.vue';
import AppJumbotron from './components/AppJumbotron.vue';
import AppMain from './components/AppMain.vue';

export default {

  name: 'App',

  components: {
    AppHeader,
    AppJumbotron,
    AppMain,
  }

}

</script>


<template>
  <AppHeader />
  <AppJumbotron />
  <AppMain />
</template>

<style scoped></style>
