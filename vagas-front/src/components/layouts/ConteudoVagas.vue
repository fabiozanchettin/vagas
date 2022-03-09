<template>
  <div>
    <h1>{{titulo}}</h1>
    <button @click="conteudo = 'home-vagas'">Home</button>
    <button @click="conteudo = 'publicar-vaga'">Pulicar vaga</button>
    <component :is="conteudo"></component>
    
    <!--<home-vagas></home-vagas>-->
    <!--<publicar-vaga></publicar-vaga>-->
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
  },
  data:()=> ({
    titulo: 'Componente Conteúdo',
    conteudo: 'home-vagas'
  }),
}

</script>


<style>

</style>
