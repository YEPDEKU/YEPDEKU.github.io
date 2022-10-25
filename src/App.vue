<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>

  <header>
    <video autoplay muted loop id="sim">
      <source src="./picsnvids/willie_short.mp4" type="video/mp4">
    </video>
    <h1>David Larsen's Social media profiles</h1>

    <div class="pfp-container">
      <img src="./picsnvids/cliff.png" class="cliff">
    </div>
  </header>
  <nav>
    <table>
      <div id="outer">

        <div class="githubb">
          <img id="githublogo" src="./picsnvids/github.png">
          <a id="github" href="https://github.com/YEPDEKU" target="_blank">Github</a>
        </div>

        <div class="goodreadsb">
          <img id="goodreadslogo" src="./picsnvids/goodreads.png">
          <a id="goodreads" href="https://www.goodreads.com/user/show/156697534-david-larsen"
            target="_blank">Goodreads</a>
        </div>

        <p></p>

        <div class="letterboxdb">
          <img id="letterboxdlogo" src="./picsnvids/letterboxd.png">
          <a id="letterboxd" href="https://letterboxd.com/dl_normandy/" target="_blank">Letterboxd</a>
        </div>



        <div class="serializdb">
          <img id="serializdlogo" src="./picsnvids/serializd.png">
          <a id="serializd" href="https://www.serializd.com/user/DavidLarsen/profile" target="_blank">Serializd</a>
        </div>

        <p></p>

        <div class="instagramb">
          <img id="instagramlogo" src="./picsnvids/Instagram.png">
          <a id="instagram" href="https://www.instagram.com/david.la611/" target="_blank">Instagram</a>
        </div>

        <div class="discordb">
          <img id="discordlogo" src="./picsnvids/Discord.png">
          <a id="discord" href="https://discord.com/users/449541931102371871" target="_blank">Discord</a>
        </div>

      </div>
    </table>

  </nav>
</template>

<style scoped>
div {
  position: relative;
  text-align: center;
}


#sim {
  position: fixed;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  right: 0;
  background: fixed;
  bottom: 0;
  min-width: 100%;
  min-height: 100%;
}

h1 {
  position: relative;
  display: block;
  color: rgb(255, 255, 255);
  font-size: 40px;
  text-align: center;
  text-shadow: -1px 1px 0 #000,
    1px 1px 0 #000,
    1px -1px 0 #000,
    -1px -1px 0 #000;

}

header {
  font-family: 'CaskaydiaCove NF';
  font-size: 12px;
}


header {
  line-height: 1.5;
  max-height: 100vh;
}


nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}


nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

nav {

  margin-left: -1rem;
  font-size: 1rem;

  padding: 10rem 0;
  margin-top: 1rem;
}
</style>
