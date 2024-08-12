<script setup>
    import axios from "axios"
    const response = await axios.get("https://thronesapi.com/api/v2/Characters")
    console.log(response)
</script>

<template>
    <div>
        <h1> GOT card view </h1>
    </div>
</template>