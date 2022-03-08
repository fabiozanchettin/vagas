<template>
    <div class="container py-4">
    <pesquisar-vaga></pesquisar-vaga>
    <div class="row mt-5">
          <indicador-vaga></indicador-vaga>
        
        
          <indicador-vaga></indicador-vaga>
        
        
          <indicador-vaga></indicador-vaga>
    </div>
  </div>
  
</template>

<script>
import PesquisarVaga from '../comuns/PesquisarVaga.vue'
import IndicadorVaga from '@/components/comuns/IndicadorVaga.vue'
export default {
  components: { PesquisarVaga,
                IndicadorVaga
              },
    name: 'HomeVagas'
}
</script>


<style>

</style>