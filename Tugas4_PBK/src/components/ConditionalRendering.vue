<script setup>
import {ref} from 'vue';
const showText = ref(true);
</script>

<template>
<div>
  <h2> Conditional Rendering</h2>
  <button @click="showText = true">Tampilkan</button>
  <button @click="showText = false">Sembunyikan</button>
  <p v-if="showText">Tidak akan muncul ketika Tombol di klik tombol "Sembunyikan"</p>


</div>

</template>

<style scoped>

</style>