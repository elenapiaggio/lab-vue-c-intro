<script setup>
const props = defineProps({
  icon: String,
  title: String,
  description: String
})
</script>

<template>
  <div class="info-card">
    <img :src="icon" :alt="title" />
    <h3>{{ title }}</h3>
    <p>{{ description }}</p>
  </div>
</template>

<style>

.info-card {
  text-align: center;
  padding: 20px;
}

.info-card img {
  width: 80px;
  margin-bottom: 10px;
}


</style>
