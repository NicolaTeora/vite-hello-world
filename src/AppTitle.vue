<script>
//importo il componente che voglio utilizzare nel foglio principale
import AppHero from './AppHero.vue'

//imposto i dati da utilizzare nella pagina principale
export default {
  data (){
    return{
      titlePage: 'La mia prima app con Vite!'
    }
  },
// carico i componenti da utilizzare
  components: { AppHero },

  methods(){},

  computed(){}
}
</script>

<template>
  <div class="container">
    <h3>{{ titlePage }}</h3>
    
    <!-- passo e utilizzo i componenti come se fossero dei tag self-closed -->
    <AppHero>
    </AppHero>
    
    
  </div>
</template>

<style>
  @import url(./style.css);
</style>
