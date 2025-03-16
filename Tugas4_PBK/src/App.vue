<script setup>
import ReactiveVariable from './components/ReactiveVariable.vue';
import TextInterpolation from './components/TextInterpolation.vue';
import FormBinding from './components/FormBinding.vue';
import EventListener from './components/EventListener.vue';
import AttributeBinding from './components/AttributeBinding.vue';
import ConditionalRendering from './components/ConditionalRendering.vue';
</script>

<template>
  <div>
    <ReactiveVariable />
    <TextInterpolation />
    <FormBinding />
    <EventListener />
    <AttributeBinding />
    <ConditionalRendering />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
