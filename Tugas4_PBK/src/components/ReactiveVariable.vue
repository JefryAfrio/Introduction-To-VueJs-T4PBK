<script setup>
import {ref} from 'vue';
const counter = ref(0);
function increment() {
  counter.value++;
}

</script>

<template>
<div class="container">
  <h2>Counter : {{ counter }}</h2>
  <button @click="increment"> Tambah </button>

</div>
</template>


<style scoped>
.container h2{
  color: aqua;
}


</style>