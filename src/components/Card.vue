<script setup>
    import { defineProps } from 'vue';

    const { image, name, occupation } = defineProps(['image', 'name', 'occupation'])
</script>

<template>
    <NCard title="Card with Cover">
      <template #cover>
        <img :src="image">
      </template>
      <h3>{{ name }}</h3>
      <p>{{ occupation }}</p>
    </NCard>
  </template>


<style scoped>
.n-card {
    width: 200px;
    margin:10px 20px;
    height: 400px;

}
.n-card img {
    height: 250px
}
</style>