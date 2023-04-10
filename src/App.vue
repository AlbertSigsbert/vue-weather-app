<template>
  <Navigation />
  <main>
    <router-view />
  </main>
</template>

<script>
import Navigation from "./components/Navigation.vue";

export default {
  components: { Navigation },
};
</script>

<style>
</style>