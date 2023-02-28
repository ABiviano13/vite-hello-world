<script>
//1. si importa il file
import AppTitle from './components/AppTitle.vue';

export default {
  components: {
    //2. si registra il componente
    AppTitle
  },
}
</script>

<template>
  <!-- 3. si utilizza il componente -->
  <div>
    <AppTitle></AppTitle>
  </div> 
</template>

<!-- CSS (se serve) -->
