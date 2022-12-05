<template>
  <Header />
  <Jumbotron />
  <ComicsCards />
  <Banner />
  <Main />
  <Footer />
</template>

<script setup>
import Header from './components/Header.vue';
import Jumbotron from './components/Jumbotron.vue';
import Banner from './components/Banner.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
import ComicsCards from './components/ComicsCards.vue';

</script>

<style lang="scss">
@use './styles/general.scss'
</style>
