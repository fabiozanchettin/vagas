<template>
  <div>
    <topo-vagas></topo-vagas>
    <conteudo-vagas></conteudo-vagas>
  </div>
</template>

<script>
import ConteudoVagas from './components/layouts/ConteudoVagas.vue'
import TopoVagas from './components/layouts/TopoVagas.vue'

export default {
  name: 'App',
  components: {
    ConteudoVagas,
    TopoVagas


  }
}
</script>

<style>

</style>
