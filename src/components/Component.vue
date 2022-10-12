<script setup>
import { ref } from 'vue'
const onSubmit = () =>{
    console.log('Hello World')
}

</script>

<template>
    <h2>Holi, al final se hacerlo</h2>
    <form @submit.prevent="onSubmit()"><button type="submit">A</button>
    </form>
</template>
    
<style scooped>
  
</style>
  