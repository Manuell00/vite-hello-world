<script>
import HelloWorld from './components/HelloWorld.vue';
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default{
    components: {
        AppTitle,
        AppHero,
        HelloWorld
    }
}
</script>

<template>
  <div>
    <!-- Inserisco il titolo -->
    <AppTitle/>

    <!-- Inserisco il Jumbotron -->
    <AppHero/>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
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
