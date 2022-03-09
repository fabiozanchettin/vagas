<template>
    
          <div class="card">
            <div class="card-header bg-dark text-white">{{titulo}}</div>
            <div class="card-body">
              <p>{{descricaoVagas}}</p>
            </div>
            <div class="card-footer">
              <small class="text-muted"> Salário: R$ {{salario}} | Tipo: {{tipo}} | Modalidade: {{modalidade}} | Publicação: {{publicacao}}</small>
            </div>
          </div>
       
</template>


<script>
    export default {
        name: 'VagaVaga',
        props:['titulo','descricaoVagas','salario','modalidade','tipo','publicacao']
    }
</script>
