<script setup>
    import { ref } from 'vue'
    const me = ref('/assets/me.png')

    const x = ref(200)
    // Add code here

</script>

<template>

    <!-- Add code here -->
   <div>
        <img v-bind:src='me'><hr>
   </div>
</template>
