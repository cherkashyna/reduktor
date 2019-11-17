<template>
  <div>
    <Header></Header>
    <Content1></Content1>
    <div class="container">
      <ContentTop></ContentTop>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import Footer from "../pages_components/Footer.vue";
import ContentTop from "../pages_components/ContentForHomePage1.vue";
import Content1 from "../pages_components/Content1.vue";
export default {
  components: {
    Header: Header,
    Footer: Footer,
    ContentTop: ContentTop,
    Content1: Content1,
  }
};
</script>
  
