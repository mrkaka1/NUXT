<template>
    <div>
      <!-- <NuxtWelcome /> -->
      <!-- <h1 class="titulo">HOme</h1>
      <NuxtLink to="/pagina2">teste</NuxtLink>
      <NuxtLink to="/produtos">produto</NuxtLink> -->
      <h1>Teste Titulo Abaixo</h1>
      <titulo/>
      <!-- <h6>Descrição Abaixo</h6>
      <descricao/> -->

      <NuxtLink to="/venda">Vendas aqui</NuxtLink>
    </div>
  </template>
<script>
import titulo from '../components/titulo.vue'
import descricao from '../components/descricao.vue'

export default {
    components: {
        titulo,
        descricao
    }
}
</script>

<style scoped>
 * {
    margin: 0;
 }
 .titulo {
    color: aqua;
    
}
</style>