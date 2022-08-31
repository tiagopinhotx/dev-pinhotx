<template>
    <ul id="social-footer-links">
      <li>
        <a  id="twitch-footer-link"
            href="https://twitch.tv/pinhotx" 
            class="fa fa-twitch" 
            target="_blank"></a>
      </li>
      <li>
        <a  id="twitter-footer-link"
            href="https://twitter.com/tiagopinhotx" 
            class="fa fa-twitter" 
            target="_blank"></a>
      </li>

      <li>
        <a  id="reddit-footer-link"
            href="https://www.reddit.com/user/tiagopinhotx" 
            class="fa fa-reddit" 
            target="_blank"></a>
      </li>

      <li>
        <a  id="instagram-footer-link"
            href="https://instagram.com/tiagopinhotx" 
            class="fa fa-instagram" 
            target="_blank"></a>
      </li>

      <li>
        <a  id="linkedin-footer-link"
            href="https://linkedin.com/in/tiagopinhotx" 
            class="fa fa-linkedin" 
            target="_blank"></a>
      </li>
      <li>
        <a  id="github-footer-link"
            href="https://github.com/tiagopinhotx" 
            class="fa fa-github" 
            target="_blank"></a>
      </li>
    </ul>

</template>

<style scoped>



ul{
    margin-bottom: 0.9rem;
    text-align: center;
    padding: 0;
    display: flex;
    justify-content: space-around;
    flex-wrap: nowrap;


}

ul li{
    display: inline;
    text-align: center;
    margin: auto;
    display:inline-block;

}


.fa {
    margin-top: 1rem;
    color: var(--yellow);
    font-size: 1.5rem;
    transition: 0.5s;
}

.fa:hover{
    font-size: 3rem;
}

.fa#github-footer-link:hover{
    color: var(--orange);
}

.fa#linkedin-footer-link:hover{
    color: var(--blue);
}

.fa#twitter-footer-link:hover{
    color: var(--blue);
}
.fa#twitch-footer-link:hover{
    color: var(--purple);
}

.fa#instagram-footer-link:hover{
    color: var(--purple);
}

.fa#reddit-footer-link:hover{
    color: var(--orange);
}

</style>
<script>
  export default {
  name: 'social-tree',
}


</script>