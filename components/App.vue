<template>
  <Router :routes="routes"></Router>
</template>

<script>
import Router from './Router.vue';

import HomePage from './pages/HomePage.vue';
import AboutPage from './pages/AboutPage.vue';
import BlogPage from './pages/BlogPage.vue';
import ContactPage from './pages/ContactPage.vue';
import NotFoundPage from './pages/NotFoundPage.vue';

export default {
  data: () => ({
    routes: {
      default: NotFoundPage,
      '/': HomePage,
      '/about': AboutPage,
      '/blog': BlogPage,
      '/contact': ContactPage,
    }
  }),

  components: { Router }
}
</script>