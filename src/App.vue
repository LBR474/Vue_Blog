<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <!-- <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a> -->
            <h2>Why I like watching bike racing on TV</h2>

        <figure class="mainImage">
          <!-- <img src="images/Milan_San_Remo_Main_Image.png" alt=""> -->
          <figcaption>Milan San Remo bike race.</figcaption>

        </figure>



        <article>

          A few months ago I was talking on the phone with my friend Michael, and I said: <i> ‘it’s a strange phase of
            life
            for me at
            the moment Michael, the only thing I really like to do is ride my own bike for 50 kilometres, then come home
            and watch
            other people ride their bikes for 200 kilometres’.</i> <br>
          Which made me think about why I like it so much. <br>
          </article>
  </div>
  <HelloWorld msg="Vite + Vue - new message" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
