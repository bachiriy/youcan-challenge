<script setup lang="ts">
defineProps<{
  degree: number;
}>();
const initDegree = 21;
</script>

<template>
  <div class="container">
    <div class="icon">
      <img src="" />
      <h2>19ᵒ</h2>
    </div>
    <div class="description">
      <h4>Partialy Cloudy</h4>
      <p>It Feels like {{ initDegree }}ᵒ</p>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
}
.icon {
}
.icon img {
}
.icon h2 {
}
.description h4 {
}
.description p {
}
</style>
