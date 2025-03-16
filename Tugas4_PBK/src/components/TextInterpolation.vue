<script setup>
const name = "Jefry Afrio";
const age = 20;
const pesan = "Semangat Meraih impian"
</script>

<template>
  <div>
    <h2>Perkenalan</h2>
    <p>Halo, nama saya {{ name }}. Saya berusia {{ age }} tahun.</p>
    <p class="quotes" >{{ pesan }}</p>
  </div>
</template>

<style scoped>
.quotes{
  color: rgb(249,141,0);
}

</style>