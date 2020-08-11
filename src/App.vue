<template>
  <div id="app">
    <header-app></header-app>
    <router-view></router-view>
    <footer-app></footer-app>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components:{
    HeaderApp:Header,
    FooterApp:Footer
  }
}
</script>

<style>
@import './assets/fontawesome/css/all.css';
</style>
