<!-- SCRIPT -->

<script setup>

let nomes = ['alice', 'bruna', 'caio', 'daniel', 'ellen']
</script>
<!-- HTML -->
<template>
  <ul>
    <li v-for="nome in nomes">{{ nome }}</li>
  </ul>
</template>