<!-- SCRIPT -->
<script setup>
import { ref } from 'vue';

// variáveis
let texto = ref(''); // exibir em tempo real (deixa a variável reativa)
</script>


<!-- HTML -->
<template>
  <input type="text" v-model="texto">
  <p>{{ texto }}</p>
</template>