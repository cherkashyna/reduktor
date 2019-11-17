<template>
  <div>
    <Header></Header>
    <About></About>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import Footer from "../pages_components/Footer.vue";
import About from "../pages_components/About.vue";

export default {
  components: {
    Header: Header,
    Footer: Footer,
    About: About
  }
};
</script>