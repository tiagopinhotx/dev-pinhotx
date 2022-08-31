<template>

  <footer>
    
  </footer>

</template>

<script>
  import SocialTree from '../Social/social-tree.vue';


  export default {
  name: 'footer-root',
 
  components: {
    SocialTree
  }
}

</script>

<style scoped>

footer{
    width: 100%;
    position: fixed;
    left: 0;
    bottom: 0;
    background-color: var(--body-bg-color-alpha5);

}


</style>