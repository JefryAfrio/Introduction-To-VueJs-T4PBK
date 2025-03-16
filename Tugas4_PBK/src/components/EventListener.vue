<script setup>
import {ref} from 'vue';
const counter = ref(0);
const increment = () => {
  counter.value++;
}
</script>

<template> 
<div> 
  <h2> Tombol Klik </h2>
  <button @click="increment">Tekan</button>
  <p>Jumlah Klik: {{ counter }}</p>
</div>
</template>

<style scoped>

</style>