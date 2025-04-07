<script setup>
const { data } = await useFetch("http://localhost:8000/api/data");
</script>

<template>
  <div>
    {{ data.message }}
  </div>
</template>
