<script setup> 
  const name = 'Vue dinamico'
  const styleColor = 'color:blue';
</script>

<template>
  <h1>Hola {{ name.toUpperCase() }}</h1> <hr>
  <h2 v-bind:style = "styleColor">  Soy azul</h2>
</template>

<style>
  h1{
    color: red
  }
</style>