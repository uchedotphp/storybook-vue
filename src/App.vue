<template>
  <div id="app" class="pt-20">
    <Header />
    <SignUp />
    <Partners />
    <Footer />
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view /> -->
  </div>
</template>

<script>
import Header from "@/components/Header";
import SignUp from "@/components/SignUp";
import Partners from "@/components/Partners";
import Footer from "@/components/Footer";
export default {
  name: "Home",
  components: {
    Header,
    SignUp,
    Partners,
    Footer,
  },
};
</script>
<style lang="scss">
</style>
