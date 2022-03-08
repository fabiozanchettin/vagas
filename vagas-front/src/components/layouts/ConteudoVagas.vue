<template>
  <div>
    <p>conteudo component</p>
    <home-vagas></home-vagas>
    <publicar-vaga></publicar-vaga>
  </div>
</template>

<script>

import HomeVagas from '../views/HomeVagas.vue'
import PublicarVaga from '../views/PublicarVaga.vue'
export default {
  name:'ConteudoVaga',
  components: {
    HomeVagas,
    PublicarVaga
    
  }
}

</script>


<style>

</style>
