<template>

    <div>
      <div>
        <h2>Генератор случайных чисел от 1 до 100:</h2>
        <p>Number: {{ generator }} </p>
      </div> 
      <button @click="generate">Generate</button>
  
    </div>
    
  </template>
  
  <script setup>
  import {ref} from 'vue';
  
  const generator = ref(0);
  const min = 0;
  const max = 100;
  const generate = () => generator.value = Math.floor((Math.random(generator.value) * (max-min)) + min)
  
  </script>