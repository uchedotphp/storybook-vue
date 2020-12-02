<template>
  <div id="app" class="pt-20 bg-red-700">
    <Header />
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view /> -->
  </div>
</template>

<script>
import Header from "@/components/Header";
export default {
  name: "Home",
  components: {
    Header,
  },
};
</script>
<style lang="scss">
</style>
