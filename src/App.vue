<script>
import AppTitle from './components/AppTitle.vue'
import AppHero  from './components/AppHero.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    AppHero
  },
  data() {
    return {
      title: 'Hello There!'
    }
  }
}
</script>

<template>

  <AppHero />

  <h1 id="main-title"> {{ title }} </h1>

  <AppTitle />

</template>

<style scoped>

#main-title {
  color: gold;
  will-change: filter;
  transition: filter 300ms;
}

#main-title:hover {
  filter: drop-shadow(0 0 1em rgb(255, 215, 0));
  cursor: pointer;
}
</style>
