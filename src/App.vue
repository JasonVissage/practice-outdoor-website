<template>
  <HeaderTest />
  <HomePage />
</template>

<script>
import HomePage from './components/HomePage.vue';
import HeaderTest from './components/HeaderTest.vue';

export default {
  name: 'App',
  components: {
    HomePage,
    HeaderTest,
  },
};
</script>

<style src="./assets/styles.css"></style>
