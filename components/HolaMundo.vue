<template>
  <div>
    <h1>Hola Mundo Perro Culio!</h1>
    <h1>Contador: {{ count }}</h1>
    <button @click="increment">Incrementar</button>
    <button @click="decrement">Decrementar</button>
  </div>
</template>

<script setup lang="ts">
const { count, increment, decrement } = useCounter()
</script>