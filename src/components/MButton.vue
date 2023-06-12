<script setup>
const props = defineProps({text: String})
</script>

<template>
    <button>{{ props.text }}</button>
</template>

<style scoped>
button{
    background-color: blue;
    border: 1px solid #ccc;
    font-size: 1.1rem;
    color: white;
    border-radius: 5px;
    padding: 5px 10px;
    cursor:pointer;
}

button:hover{
    background-color: darkblue;
}
</style>
 