<script setup>
  import GotCard from './components/GotCard.vue';
</script>


<template>
  <main>
    <h1>
      GOT
    </h1>
    <Suspense>
      <template #default>
        <GotCard />
      </template>
      <template #fallback>
        <div>
          <p>Loading...</p>
        </div>
      </template>
    </Suspense>
  </main>
</template>



<style scoped>
</style>