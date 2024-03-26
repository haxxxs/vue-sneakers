<script setup>
import MyHello from './components/MyHello.vue'
</script>

<template>
  <MyHello title="Кроссовки Puma" :price="19500" :isAdded="true" />
  <MyHello />
  <MyHello />
</template>
