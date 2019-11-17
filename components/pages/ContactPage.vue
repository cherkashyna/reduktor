<template>
  <div>
    <Header></Header>
    <Contacts></Contacts>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import Contacts from "../pages_components/Contacts.vue";
import Footer from "../pages_components/Footer.vue";
export default {
  components: {
    Header: Header,
    Footer: Footer,
    Contacts: Contacts
  }
};
</script>