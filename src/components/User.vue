<template>
    <div>
      <div>
        <h2>User information</h2>
        <p>ID:{{ user.Id }}</p>
        <p>Name: {{ user.Name }}</p>
        <p>Surname: {{ user.Surname }}</p>
        <p>Age: {{ user.Age }}</p>
        <p>Mail: {{ user.Mail }}</p>
        <p>Country: {{ user.Country }}</p>
      </div> 
    </div>
</template>
  
<script setup>
import {ref} from 'vue';
const user = {
    Id: 34,
    Name: "Qwe",
    Surname: "Asd",
    Age: 20,
    Mail: "asdasd@gmail.com",
    Country: "Malaysia"
}
</script>