

<template>

  <header>
    <nav class="nav-bar">
      <h1>{{page_title}}</h1>
    </nav>
  </header>

</template>

<script>
  export default {
  name: 'NavBar',
  props: {
    page_title: String
  }
}


</script>

<style scoped>

  nav {
  background: linear-gradient(-90deg, #84cf6a, #16c0b0);
  height: 60px;
  margin-bottom: 25px;
  -webkit-box-shadow: 0px 2px 15px -12px rgba(0, 0, 0, 0.57);
  -moz-box-shadow: 0px 2px 15px -12px rgba(0, 0, 0, 0.57);
  box-shadow: 1px 1px 5px rgba(0, 0, 0, 0.57);
  display: flex;
}

h1 {
  color: #fff;
  margin: auto;
}


</style>