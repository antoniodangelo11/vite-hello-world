<script>
import AppHero from './components/AppHero.vue'
import MainVue from './components/MainApp.vue'

export default {
  components: {
    AppHero,
    MainVue,
  }
}
</script>

<template>
  <h1>La mia prima app con Vite!</h1>
  <AppHero />
  <MainVue />
</template>

<style scoped></style>
