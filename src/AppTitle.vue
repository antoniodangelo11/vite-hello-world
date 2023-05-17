<script>
import AppHero from './components/AppHero.vue'
import MainVue from './components/MainApp.vue'
import VincenzoApp from './components/VincenzoApp.vue'

export default {
  components: {
    AppHero,
    MainVue,
    VincenzoApp,
  }
}
</script>

<template>
  <h1>La mia prima app con Vite!</h1>
  <AppHero />
  <MainVue />
  <VincenzoApp />
</template>

<style scoped></style>
