<template>
  <div>
    <AppHeader />
    <Nuxt />
  </div>
</template>

<script>
import AppHeader from "../components/AppHeader.vue";

export default {
  name: "Default",
  components: {
    AppHeader,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {

  background: #ede9fe;
  border-radius: 20px;
}
</style>