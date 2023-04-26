<script>
import AppTitle from './components/AppTitle.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    // AppHero
  },
  data() {
    return {
      title: 'Hello There!'
    }
  }
}
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <h1> {{ title }} </h1>
  <AppTitle />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em rgba(100, 108, 255, 0.667));
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

h1 {
  color: gold;
  will-change: filter;
  transition: filter 300ms;
}

h1:hover {
  filter: drop-shadow(0 0 1em rgb(255, 215, 0));
  cursor: pointer;
}
</style>
