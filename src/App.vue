
<script setup>
import { ref } from 'vue'

const compteur = ref(0)

function incrementer() {
  compteur.value++
}

function decrementer() {
  compteur.value--
}
</script>

<template>
  <div>
    <h1>Compteur</h1>

    <p>{{ compteur }}</p>

    <button @click="incrementer">+</button>
    <button @click="decrementer">-</button>
  </div>
</template>

<style>
div {
  text-align: center;
  margin-top: 100px;
  background-color:pink;
}
body
{
  background-color:pink;
}
h1 {
  color:green;
  font-size: 40px;
}

p {
  font-size: 50px;
  color:black;
}

button {
  color:green;
  font-size: 30px;
  margin: 10px;
  padding: 10px 25px;
}
</style>

