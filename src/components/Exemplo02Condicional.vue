<!-- SCRIPT -->
<script setup>

// variáveis
let media = 2
let exibir = true
</script>

<!-- HTML -->
<template>
  <h1 v-if="exibir">Hello World!</h1>

  <p v-if="media >= 7">Aprovado(a)</p>
  <p v-else-if="media >=5">Em exame</p>
  <p v-else>Reprovado(a)</p>
</template>