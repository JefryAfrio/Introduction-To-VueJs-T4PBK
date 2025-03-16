<script setup>
import {ref} from 'vue';
const imageUrl = ref('https://via.placeholder.com/150');

</script>

<template>
<div>
  <h2>Attribute Binding</h2>
  <img :src="imageUrl" alt="Contoh Gambar">
</div>

</template>

<style scoped>

</style>