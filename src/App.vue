<template>
  
  <Header page_title="Hauhau" logo="center">
    <img alt="Vue logo" src="./assets/logo.png">
  </Header>
  <Main/>
  <footer-root kind="social-bar"/>
</template>

<script>
import FooterRoot from './components/Footer/Footer.vue';
import Header from './components/Header/Header.vue';
import Main from './components/Main.vue';

export default {
  name: 'App',
  components: {
    Main,
    HeadStar,
    FooterRoot,
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
