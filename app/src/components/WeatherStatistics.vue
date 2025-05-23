<script setup lang="ts">
import WeatherStat from "./WeatherStat.vue";
</script>
<template>
<div class="container">
    <WeatherStat>
       <template #icon><img src="" /></template>
       <template #type>Wind</template>
       <template #value>40%</template>
    </WeatherStat>
    <WeatherStat>
       <template #icon><img src="" /></template>
       <template #type>Wind</template>
       <template #value>40%</template>
    </WeatherStat>
    <WeatherStat>
       <template #icon><img src="" /></template>
       <template #type>Wind</template>
       <template #value>40%</template>
    </WeatherStat>
    <WeatherStat>
       <template #icon><img src="" /></template>
       <template #type>Wind</template>
       <template #value>40%</template>
    </WeatherStat>
</div>
</template>
<style scoped>
.container {
}
</style>
