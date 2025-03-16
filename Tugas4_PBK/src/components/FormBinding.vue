<script setup>
import {ref} from 'vue';
const masukanKalimat = ref("");
</script>

<template>
<div>
  <h2>Kata Kata Hari Ini</h2>
  <input v-model="masukanKalimat" />
  <p>Hasil: {{ masukanKalimat }}</p>

</div>

</template>

<style  scoped>

</style>