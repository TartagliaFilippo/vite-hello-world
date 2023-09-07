<script>
import AppImage from "./components/AppImage.vue";
export default {
  data() {
    return {
      title: "La mia prima app con Vite!",
    };
  },
  components: { AppImage },
};
</script>

<template>
  <h1>{{ title }}</h1>
  <AppImage />
</template>

<style></style>
