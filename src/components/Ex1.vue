<script setup>
    import { ref } from 'vue'

    // Add code here
    // challenge: use array  
    const message = ref("Choose your favourite: ")
    const fruits = ref(["apple", "orange", "peach"])
    
</script>

<template>
    {{ message }} 
   
    <!-- <label for=""> <input type="radio" name="fruit"> {{ fruit1 }} </label> 
    <label for=""> <input type="radio" name="fruit"> {{ fruit2 }} </label> 
    <label for=""><input type="radio" name="fruit"> {{ fruit3 }} </label>  -->

    <label v-for="fruit in fruits" :key="fruit">
        <input type="radio" name="fruit">{{ fruit }}</label>
    
</template>

<style scoped>
</style>
