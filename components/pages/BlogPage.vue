<template>
  <div>
    <Header></Header>
    <Blog></Blog>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import Blog from "../pages_components/Blog.vue";
import Footer from "../pages_components/Footer.vue";
export default {
  components: {
    Header: Header,
    Blog:Blog,
    Footer: Footer
  }
};
</script>