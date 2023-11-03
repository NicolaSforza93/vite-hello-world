<script>
import AppHero from './components/AppHero.vue'

export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'
    };
  },
  components: { AppHero }
}
</script>

<template>
  <div>
    <h1>{{ message }}</h1>
  </div>
  <AppHero />
</template>

<style scoped>
h1 {
  text-align: center;
}
</style>
