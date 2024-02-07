<script>
import AppHero from './AppHero.vue'

export default {
  data (){
    return{
      title: 'La mia prima app con Vite!'
    }
  },

  components: {
    AppHero: AppHero,
  },

  methods(){},

  computed(){}
}
</script>

<template>
  <div class="container">
    <h1>{{ title }}</h1>
    <AppHero />
  </div>
</template>

<style>
  @import url(./style.css);
</style>
