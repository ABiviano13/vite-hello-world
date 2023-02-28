<script>
//1. si importa il file
import AppTitle from './components/AppTitle.vue'

import AppHero from './components/AppHero.vue'


export default {
  components: {
    //2. si registra il componente
    AppTitle,
    AppHero
    
  },
}
</script>

<template>
  <!-- 3. si utilizza il componente -->
  <div>
    <AppHero></AppHero>
  </div>
  <div>
    <AppTitle></AppTitle>
  </div> 
</template>

<!-- CSS (se serve) -->
