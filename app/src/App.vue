<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
import CityInfo from "./components/CityInfo.vue";
import WeatherOverview from "./components/WeatherOverview.vue";
import WeatherStatistics from "./components/WeatherStatistics.vue";

</script>

<template>
  <main>
    <CityInfo />
    <WeatherOverview />
    <WeatherStatistics />
  </main>
</template>

<style scoped>
@media (min-width: 1024px) {
}
</style>
