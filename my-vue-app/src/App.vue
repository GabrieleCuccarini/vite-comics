<template>
  <Header />
  <Banner />
  <Banner2 />
  <Main />
  <Footer />
</template>

<script setup>
import Header from './components/Header.vue';
import Banner from './components/Banner.vue';
import Banner2 from './components/Banner2.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
</script>

<style lang="scss">
@use './styles/general.scss'
</style>
