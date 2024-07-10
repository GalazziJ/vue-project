<!-- SCRIPT -->
<script setup>
let texto = '<p style="color: red">aprendendo a diretiva v-html</p>'
</script>

<!-- HTML -->
<template>
  <div v-html="texto"></div> <!-- foco em utilizar estruturas HTML -->
  <div>{{ texto }}</div>
</template>